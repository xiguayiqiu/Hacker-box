# Hacker-box
### 介绍
本项目是bilibili-游戏科技君弈秋啊(个人开发)
### 原因
本作者是看到除了kali以外没有其他的黑客系统，感到不够新颖所以才自行开发这个黑客系统的（纯属Linux开发练习）
### 安装
通用的amd64架构debain系列（x86_64）
```shell
wget -O install "https://kkgithub.com/xiguayiqiu/Hacker-box/releases/download/rootfs/install.sh"&&chmod +x install&&./install
```
### Termux安装
```
pkg install wget -y&&apt install termux-exec&&wget -O install "https://github.com/xiguayiqiu/Hacker-box/releases/download/rootfs/termux-install.sh"&& chmod +x install&&./install
```
### 注意
以上安装都是基本系统，没有工具的chroot基本文件系统
想体验持续开发版请安装VMwear虚拟机，下载虚拟机版（目前没有制作ISO安装镜像）
### 已知问题
##### 1.termux的LD_PRELOAD环境变量无法调用->可以在每一个脚本的最前面添加nuset LD_PRELOAD 
``
其实不影响运行，只不过会报错而已
## 无法安装解决办法
###### Windows/Mac：watttoolkit（stame++）
###### tarmux（安卓）：V2VPN（app）
###### Linux（debain系列）更改hosts或者dns
