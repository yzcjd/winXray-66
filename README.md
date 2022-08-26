# WinXray
### Windows端代理客户端

本项目全部代码Fork自原作者，仅调整该说明页面，维护可用免费代理。

作者宣布不再更新，建议 fork 备份、保存公益订阅防失联。

.

# 目录

### [一、介绍](#介绍)

### [二、说明](#说明)

### [三、下载](#下载)

### [四、老牌公益订阅](#1)

### [五、大型公益订阅](#2)

### [六、其它免费订阅](#3)

### [七、使用教程](#4)

[① 订阅链接导入](#订阅链接导入)

[② 服务器配置](#服务器配置)

[③ PAC配置](#PAC配置)

[④ 电报代理配置](#电报代理配置)

### [八、视频教程(YouTube)](https://www.youtube.com/results?search_query=winXray&sp=CAI%253D) 

.

# [介绍](#介绍)

WinXray[:loud_sound:](http://dict.youdao.com/dictvoice?audio=winxray&type=2) 是一个简洁稳定的 Xray/V2Ray(vmess/vless/xtls)、Shadowsocks、Trojan 通用客户端（Windows系统），可自动检测并连接访问速度最快的代理服务器。服务器连接异常时可以自动更换代理服务器 - 再也不用担心服务器抽风了。WinXray 也提供一键安装 XRay(V2Ray、Shadowsocks、Trojan) 服务器工具。   

本软件源码已贡献到公共领域并放弃版权，源码可使用 [aardio](http://www.aardio.com) （开发环境仅6.5MB）编译生成单文件绿色 exe(不需要.Net等任何外部运行库 ）。

# [说明](#说明)
（仅修改排版）

尝试过很多代理客户端，发现了一些痛点：① 需要测试很久才找到可用服务器 ；② 经常掉线且切换不起作用，需要重启软件才恢复 ；③ 在 Win10 上出现相同的 BUG，即 PAC 代理模式用一段时间就会卡死。④ 很多功能用不上，菜单繁琐。网络速度与服务器响应速度本来就是波动的，如果平常只想查查 Google 看看技术文档，需要经常测试多个服务器，很繁琐。
    
我在网上找了很久都没找到合适的软件，决定自己写一个。用 aardio 写起来很快，只花了几个小时即完成了 WinXray 的主要代码，通过自行实现 PAC 服务器，解决 PAC 卡死情况。改进了几个版本，已经非常稳定了。**实测用 WinXray 几个月，再也没有遇到网络抽风访问不了 Google 的问题**。    

这里需要解释下 WinXray 的测速功能。简单的测速不必要地消耗流量且无意义，还是会遇到 ① Ping通了，但TCP访问不了 ② TCP通了，但浏览器被阻断 ③ 使用下载测速，但是长时间连不上服务器。如果手中有很多服务器需要测试，普通的测速显然不够高效。经过本人长时间地对比，**当列表中有上百个代理服务器时，WinXray 总能最快地找到能正常使用且速度最快的线路，并且几乎不消耗流量**，免去我们繁琐地 多选排队测试 => 手动双击切换。如果你有顺滑观看 4K 视频的代理服务器，可以关闭“异常自动重连”。

# [WinXray下载](#下载)

1. 官网(需代理)：     www.winxray.com

2. 下载地址： https://www.winxray.com/%e4%b8%8b%e8%bd%bd%e4%b8%ad%e5%bf%83

3. 一键下载 【 [64位版本](./../../raw/master/release/winXray.7z) / [32位版本](./../../raw/master/release/winXray32.7z) 】

4. 备用：[GitHub项目](https://github.com/TheMRLL/WinXray)

解压即可直接使用(仅 5 MB，已自带 Xray-core），如需要其它 core，在软件配置页面下载，支持切换 V2Ray core、NaiveProxy Core、SSR Core。
    
**可复制下面几个订阅链接，在 WinXray 中点击「批量导入链接」，体验 WinXray 强大的兼容性。**
.

# [老牌公益订阅](#1)

### 1. freefq

GitHub项目: [地址](https://github.com/freefq/free)

订阅地址： https://cdn.jsdelivr.net/gh/freefq/free@master/v2

### 2. SSRSUB

GitHub项目：[地址](https://github.com/ssrsub/ssr/tree/master)

Clash: https://raw.githubusercontent.com/ssrsub/ssr/master/Clash.yml

SS: https://raw.githubusercontent.com/ssrsub/ssr/master/ss-sub

V2Ray: https://raw.githubusercontent.com/ssrsub/ssr/master/V2Ray

Trojan: https://raw.githubusercontent.com/ssrsub/ssr/master/trojan

Surge: https://raw.githubusercontent.com/ssrsub/ssr/master/Surge.conf

以上几个订阅内节点不相同，可同时导入。公开的订阅更新频率低、使用人数多。

[注册SSRSUB公益机场](https://bit.ly/3BPeo5G)(需代理)，网速可达 10MB/s，每月有 50GB 流量。点击链接将自动填充官方邀请码。

.

# [大型公益订阅](#2)

### 1.Openit

[GitHub项目](https://github.com/yu-steven/openit)、[最新官网](https://openit.daycat.space/)  

Base64： https://openit.daycat.space/long

Clash： https://openit.daycat.space/clash

小火箭： https://openit.daycat.space/https

Quanx： https://openit.daycat.space/qx

### 2. v2cross.com
[GitHub项目](https://github.com/Pawdroid/Free-servers/blob/main/README.md) 
每小时更新，有安卓、ios端APP，[公益节点发布页面](https://v2cross.com/archives/1884)  

.

# [更多免费订阅](#3)

.

### [我维护的免费订阅合集](https://t.me/yzcjd/345)

### [各价位高性价比鸡场](https://t.me/yzc020/7)

变动频繁，点击链接查看最新

.

.

# [服务器导入](#4)
## [1. 订阅链接导入](#订阅链接导入)
.
![winXray](./screenshots/winXray.png)
.

**WinXray 有强大的兼容性，将自动识别并转换各种不兼容的配置为统一、规范的格式**，支持批量导入 vless、vmess、ss、trojan、trojan-go …… 等格式的分享链接，支持导入 v2ray、Shadowsocks、trojan 等通用订阅链接，兼容 base64、json …… 等不同格式的服务器配置，也可以导入 Clash proxy-provider 配置，甚至可以直接导入 GitHub 项目地址中的代理服务器。例如直接复制链接 [https://github.com/winXray/winXray/blob/master/sub/sample.json](./sub/sample.json) ，即可一键导入 WinXray。

对于大多数用户来说，无需更改配置，只需要复制 => 导入

.

### [2. 服务器配置](#服务器配置)

.
![服务器配置](./screenshots/config.json.png)
.

本人认为用很多对话框来配置服务器参数的设计是非常蠢的，所以按简单的来。**在 WinXray 的服务器配置页，点击 JSON 中任意字段，均会直接显示该字段的用法说明**。WinXray 已经将各种代理协议的配置简化为几个统一命名的 JSON 字段，（ **也可以作为一种标准、统一、通用的订阅响应格式，便于使用与分享** ），只要稍加学习就能熟练添加、修改各种代理协议的配置。

可选在"[/xray-core/winXray-default-servers.json](./xray-core/winXray-default-servers.json)"文件中添加默认服务器配置（生成 EXE 后默认配置自动嵌入到 EXE 文件，可选删除该文件,也可以继续使用该文件覆盖 EXE 自带的默认服务器列表）。

.

### [3. PAC配置](#PAC配置)
.
![PAC配置](./screenshots/pac.png)
.

**小技巧: PAC编辑器里点击任意域名都会自动关联到单选框，可以直接切换代理或直连。**

软件首次运行时会自动在当前目录查找 "./xray-core/xray.exe"，发行文件仅需要 "./winXray.exe"，可选带上 "./xray-core/" 目录（如果没有找到，会自动到v2ray官网下载，无代理时下载可能会很慢)。

### [4. 电报代理配置](#电报代理配置)

使用电报必然通过代理，用 PAC 策略判断每个 几K ~ 几十M 的文件是否需要走代理，是效率很低的事情，会使用没必要的连接判断，增加延迟与耗电。

在电报填上代理服务器，将 Socks 代理服务器的 IP 和端口填入电报代理（设置-高级-连接类型-使用自定义代理）。给Windows的电报设置一次后，无需做后续设置。更换 WinXray 中的代理时，也不用更改代理。操作如下图：

.
![端口配置](./screenshots/config.advanced.png)

.

<img src="./screenshots/telegram.gif" width="1031" alt="Telegram 端口配置">

.

.



.
