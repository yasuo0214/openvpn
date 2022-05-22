[English](README.md) | [中文](README-zh.md)

## openvpn-install

使用 Linux 脚本一键快速搭建自己的 OpenVPN 服务器。支持 Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS 和 Fedora 系统。

该脚本可让你在几分钟内建立自己的 VPN 服务器，即使你以前没有使用过 [OpenVPN](https://openvpn.net/community-resources/reference-manual-for-openvpn-2-4/)。

### 安装说明

在你的 Linux 服务器\* 上运行脚本，并按提示操作：

```bash
wget https://get.vpnsetup.net/ovpn -O openvpn.sh
sudo bash openvpn.sh
```

安装完成后，你可以再次运行脚本来管理用户或卸载 OpenVPN。

\* 一个云服务器，虚拟专用服务器 (VPS) 或者专用服务器。

### 致谢

此脚本基于 [Nyr 和 contributors](https://github.com/Nyr/openvpn-install) 的出色工作，并进行了增强和更改以与 Setup IPsec VPN 项目兼容。请向链接的上游代码库报告任何问题。

### 授权协议

MIT