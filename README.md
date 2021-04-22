# Solusvmplus-Premium

一个solusvmpro的加强版本。

## 功能：

√KVM，OpenVZ（Xen未经测试）

√NAT

√用户中心重装系统、KVM重置网络、VNC、OpenVZ TUN/TAP、OpenVZ串行控制台（H5&Java&SSH）、实时显示CPU

、RAM、流量使用情况、更改root密码、自动显示NAT端口等

*NOTE：自动显示NAT必须基于特定NAT脚本*

√管理中心一键暂停、开通、终止等多种操作

√WHMCS自动化

√支持WHMCS8（WHMCS7未经测试）

## 部署教程：

方式一：下载release包直接在WHMCS安装根目录解压

方式二：在WHMCS的modules/servers下新建solusvmplus文件夹，进入并git clone本项目即可。

## 使用：

大部分同solusvmpro，设置产品时可手动设置是否为NAT，初始流量等。

PS：若无特殊情况，请使用5656作为API通信端口，避免出现问题。

如果你觉得好用的话，欢迎给个Star哦~

## **额外许可：**

**<u>本项目开源，任何人均可免费使用，严禁倒卖</u>**

本项目基于solusvmnat以及 [Zeroteam](https://shop.zeroteam.top/)的solusvmplus。
