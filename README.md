# vimconfig

## ubuntu 下将CapsLock改为Esc





## 使用

1. 取消 ctrl + s 锁定屏幕和 ctrl + q 取消锁定屏幕的功能

   ```
   vim ~/.bashrc
   stty -ixon
   source ~/.bashrc
   ```

2.复制vimrc文件到home目录下.vim文件夹中

3.安装插件管理器

进入https://github.com/junegunn/vim-plug 网站参考

```纯++
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

就会在.vim文件夹下生成autoload

4.插件安装

将要的插件以 Plug ' '形式，写在call plug#begin('~/.vim/plugged'）和call plug#end()之间

输入命令:PlugInstall



| 功能类别 | 按键   | 按键说明               |
| -------- | ------ | :--------------------- |
| 插入     | a      | 光标后面插入           |
|          | w      | 光标前面插入           |
| 保存退出 | ctrl+s | 保存                   |
|          | ctrl+q | 退出                   |
| 导入配置 | ctrl+r | 导入配置               |
| 光标移动 | i      | 向上                   |
|          | k      | 向下                   |
|          | j      | 向左                   |
|          | l      | 向右                   |
|          | I      | 快速向上               |
|          | K      | 快速向下               |
| 搜索     | =      | 向下搜索               |
|          | -      | 向上收拾               |
|          | 双空格 | 清空高亮               |
| 分屏     | sl     | 左右分，输入箭头在左边 |
|          | sr     | 左右分，输入箭头在右边 |
|          | su     | 上下分，输入箭头在上边 |
|          | sd     | 上下分，输入箭头在下边 |
| 分屏切换 | 空格+l | 往左屏                 |
|          | 空格+r | 往右屏                 |
|          | 空格+u | 往上屏                 |
|          | 空格+d | 网下屏                 |
| 分屏大小 | 向上键 | 上移                   |
|          | 向下键 | 下移                   |
|          | 向左键 | 左移                   |
|          | 向右键 | 右移                   |
| 标签页   | tu     | 新建标签页             |
|          | tn     | 下一个标签页           |
|          | tb     | 上一个标签页           |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |
|          |        |                        |











