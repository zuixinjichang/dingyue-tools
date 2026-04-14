# 机场梯子节点订阅客户端工具大全（2026最新完整版）

> **全平台科学上网代理客户端 + 订阅转换工具完整指南**

这是一个精心整理的科学上网工具合集，涵盖 Windows、macOS、Linux、Android、iOS 全平台。所有客户端下载链接均指向官方 GitHub Releases 或 App Store，确保你下载的是最新稳定版本，避免假冒风险。

同时新增**订阅转换工具**专栏，解决不同客户端订阅格式不兼容的问题（Clash ↔ Sing-box ↔ Surge ↔ Quantumult X 等互转）。

**协议支持重点**：2026年主流推荐优先使用 VLESS + Reality、Hysteria2、TUIC v5 等协议，这些协议在速度、伪装性和抗封锁能力上表现更优。

## 机场推荐

> **购买机场节点订阅推荐参考：** [2026最新机场梯子推荐](https://github.com/maomao533/2026-jichang-tuijian)  
> 该项目整理了最新的优质机场服务商，包含详细评测、速度/稳定性测试、价格对比、优惠码等信息，帮助你选择最适合自己的节点订阅服务。

---

## 目录

- [订阅转换工具](#subconverter)
- [跨平台客户端](#cross-platform)
- [Windows平台](#windows)
- [macOS平台](#macos)
- [Linux平台](#linux)
- [Android平台](#android)
- [iOS平台](#ios)
- [使用教程](#tutorial)
- [常见问题](#faq)

---

<span id="subconverter"></span>
## 订阅转换工具（强烈推荐必备）

这些工具可以将机场订阅链接一键转换为各种客户端所需的格式，是多客户端用户或需要不同格式的用户必备工具。

### 1. subconverter（经典王牌工具）
**特点**：支持几乎所有主流格式互转（Clash / Clash.Meta / Mihomo / Sing-box / Surge / Quantumult X / Loon / V2Ray / Shadowsocks 等），可自建部署到服务器或使用在线版本。功能强大，社区活跃，支持自定义规则转换。  
**适用人群**：需要频繁转换订阅或自建转换服务的用户。  
**下载/使用地址**： [tindy2013/subconverter](https://github.com/tindy2013/subconverter)

### 2. Sub-Store（高级订阅管理器）
**特点**：专为 Quantumult X、Loon、Surge、Stash、Shadowrocket 等设计的订阅管理工具，支持多订阅聚合、规则处理、格式转换、定时更新等高级功能。  
**适用人群**：iOS/macOS 重度用户，喜欢脚本和自动化配置的用户。  
**下载/使用地址**： [sub-store-org/Sub-Store](https://github.com/sub-store-org/Sub-Store)

### 3. Hiddify Next 内置转换器
**特点**：界面友好，支持 Clash 订阅一键转为 Sing-box 格式，内置节点测速和自动选择功能。  
**适用人群**：新手或希望一站式操作的用户。  
**下载地址**： [Hiddify Next Releases](https://github.com/hiddify/hiddify-next/releases)

### 4. sing-box-converter / v2sing 等专用工具
**特点**：专注于将 Clash / V2Ray 订阅快速转换为 Sing-box JSON 配置，轻量高效。  
**推荐地址**：  
- [dzhuang/sing-box-converter](https://github.com/dzhuang/sing-box-converter)  
- [printfer/v2sing](https://github.com/printfer/v2sing)

**使用建议**：如果你订阅链接较多，推荐自建 subconverter；如果主要是 Sing-box 用户，可直接用 Hiddify Next 或 sing-box-converter。

---

<span id="cross-platform"></span>
## 跨平台客户端（推荐优先使用）

### 1. Hiddify Next
**特点**：基于 Sing-box 内核的一站式多协议客户端，使用 Flutter 开发，界面现代化漂亮，支持自动节点选择（延迟优先）、TUN 模式、远程配置文件、内置速度测试。  
**支持平台**：Windows / macOS / Linux / Android / iOS  
**支持协议**：VLESS、VMess、Trojan、Hysteria、Hysteria2、TUIC、Reality、ShadowTLS、SSH 等，几乎全覆盖。  
**优点**：配置简单、新协议支持优秀、无广告、开源免费。  
**下载地址**： [Hiddify Next Releases](https://github.com/hiddify/hiddify-next/releases)

### 2. Clash Verge Rev
**特点**：现代化 Clash.Meta（Mihomo）客户端，界面美观大方，功能全面，支持规则分流、订阅管理、内核快速切换。  
**支持平台**：Windows / macOS / Linux  
**支持协议**：SS、V2Ray、Trojan、Hysteria2、TUIC 等（通过 Mihomo 内核）。  
**优点**：UI 优秀、社区活跃、持续更新。  
**下载地址**： [Clash Verge Rev Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases)

### 3. Mihomo Party（Clash Party）
**特点**：简洁高效的 Mihomo 客户端，支持一键导入订阅、规则自动更新。  
**支持平台**：Windows / macOS / Linux / Android  
**支持协议**：基于 Mihomo 内核，支持主流协议。  
**优点**：性能优秀、配置简单。  
**下载地址**： [Mihomo Party Releases](https://github.com/mihomo-party-org/clash-party/releases)

### 4. FlClash
**特点**：Fluent UI 风格的跨平台 Clash.Meta 客户端，界面现代化，支持桌面小部件。  
**支持平台**：Windows / macOS / Linux / Android  
**支持协议**：多种代理协议。  
**优点**：设计现代、易用。  
**下载地址**： [FlClash Releases](https://github.com/chen08209/FlClash/releases)

### 5. Karing
**特点**：支持 Clash / Sing-box 前端，多平台配置同步，界面现代化。  
**支持平台**：Windows / macOS / Linux / Android / iOS  
**支持协议**：多种协议。  
**优点**：配置同步方便。  
**下载地址**： [Karing Releases](https://github.com/KaringX/karing/releases)

---

<span id="windows"></span>
## Windows平台

### 1. Clash Verge Rev
**特点**：现代化 Clash.Meta（Mihomo）客户端，Windows 上表现优秀。  
**下载地址**： [Clash Verge Rev Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases)

### 2. Mihomo Party
**特点**：简洁高效的 Mihomo 客户端，支持一键导入订阅。  
**下载地址**： [Mihomo Party Releases](https://github.com/mihomo-party-org/clash-party/releases)

### 3. FlClash
**特点**：Fluent UI 风格的跨平台 Clash.Meta 客户端，界面现代化。  
**下载地址**： [FlClash Releases](https://github.com/chen08209/FlClash/releases)

### 4. V2RayN
**特点**：最常用的 V2Ray Windows 客户端，轻量级，配置简单，支持订阅自动更新、系统托盘快速切换。  
**支持协议**：VMess、VLESS、Trojan 等。  
**下载地址**： [V2RayN Releases](https://github.com/2dust/v2rayN/releases)

### 5. NekoRay
**特点**：基于 Qt 的跨平台代理客户端，支持订阅管理、规则分流。  
**下载地址**： [NekoRay Releases](https://github.com/MatsuriDayo/nekoray/releases)

### 6. Clash for Windows（汉化版）
**特点**：汉化版的 Windows Clash 客户端，功能完整。  
**下载地址**： [Clash for Windows Releases](https://github.com/Z-Siqi/Clash-for-Windows_Chinese/releases)

---

<span id="macos"></span>
## macOS平台

### 1. Clash Verge Rev
**特点**：现代化 Clash.Meta 客户端，在 macOS 上运行良好。  
**下载地址**： [Clash Verge Rev Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases)

### 2. FlClash
**特点**：Fluent UI 风格的跨平台 Clash.Meta 客户端。  
**下载地址**： [FlClash Releases](https://github.com/chen08209/FlClash/releases)

### 3. Mihomo Party
**特点**：简洁高效的 Mihomo 客户端。  
**下载地址**： [Mihomo Party Releases](https://github.com/mihomo-party-org/clash-party/releases)

### 4. ClashX
**特点**：经典的 macOS Clash 客户端，原生体验，支持菜单栏快速操作、系统代理、规则分流。  
**下载地址**： [ClashX Releases](https://github.com/githubvpn007/ClashX/releases)

### 5. Stash
**特点**：Clash 规则完美适配的 macOS/iOS 客户端，支持高级规则。  
**下载地址**： App Store（搜索 Stash）

### 6. Surge
**特点**：付费专业级规则工具，功能强大，适合重度用户。  
**下载地址**： App Store（搜索 Surge）

### 7. V2RayU
**特点**：macOS 平台的 V2Ray 客户端，界面简洁，支持订阅功能、菜单栏快速切换。  
**下载地址**： [V2RayU Releases](https://github.com/yanue/V2RayU/releases)

---

<span id="linux"></span>
## Linux平台

### 1. Clash Verge Rev
**特点**：跨平台 Clash 客户端，Linux 支持完善，提供 AppImage 格式。  
**下载地址**： [Clash Verge Rev Releases](https://github.com/clash-verge-rev/clash-verge-rev/releases)

### 2. FlClash
**特点**：Fluent UI 风格的跨平台 Clash.Meta 客户端。  
**下载地址**： [FlClash Releases](https://github.com/chen08209/FlClash/releases)

### 3. Mihomo Party
**特点**：简洁高效的 Mihomo 客户端。  
**下载地址**： [Mihomo Party Releases](https://github.com/mihomo-party-org/clash-party/releases)

### 4. NekoRay
**特点**：基于 Qt 的跨平台代理客户端。  
**下载地址**： [NekoRay Releases](https://github.com/MatsuriDayo/nekoray/releases)

---

<span id="android"></span>
## Android平台

### 1. Hiddify Next
**特点**：一站式多协议客户端，支持新协议，界面友好。  
**下载地址**： [Hiddify Next Releases](https://github.com/hiddify/hiddify-next/releases)

### 2. Karing
**特点**：全平台同步节点，可作为 Singbox/Clash 前端。  
**下载地址**： [Karing Releases](https://github.com/KaringX/karing/releases)

### 3. ClashMeta for Android
**特点**：安卓上的 Clash.Meta 官方 GUI 客户端，支持规则分流、订阅管理。  
**下载地址**： [ClashMeta for Android Releases](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)

### 4. V2RayNG
**特点**：Android 上最常用的 V2Ray 客户端，轻量级，省电省内存，支持订阅功能。  
**下载地址**： [V2RayNG Releases](https://github.com/2dust/v2RayNG/releases)

### 5. NekoBox for Android
**特点**：轻量、界面简洁的 Android 客户端，支持多协议。  
**下载地址**： [NekoBox for Android Releases](https://github.com/MatsuriDayo/NekoBoxForAndroid/releases)

### 6. Sing-box for Android
**特点**：下一代代理内核客户端，支持 Hysteria2、TUIC、Reality 等新协议。  
**下载地址**： [Sing-box Releases](https://github.com/SagerNet/sing-box/releases)

---

<span id="ios"></span>
## iOS平台（需非国区 Apple ID）

### 1. Shadowrocket（付费）
**特点**：iOS 平台最经典的科学上网工具，支持多种协议、规则分流、JavaScript 脚本，稳定性极佳。  
**下载地址**： [Shadowrocket App Store](https://apps.apple.com/app/shadowrocket/id932747118)

### 2. Quantumult X（付费）
**特点**：功能最丰富的 iOS 代理工具，支持 JavaScript 脚本、HTTP 重写、规则分流、任务自动化。  
**下载地址**： [Quantumult X App Store](https://apps.apple.com/app/quantumult-x/id1443988620)

### 3. Stash（付费）
**特点**：Clash 规则完美适配，支持高级规则配置。  
**下载地址**： App Store（搜索 Stash）

### 4. Surge（付费）
**特点**：专业级规则工具，功能强大。  
**下载地址**： App Store（搜索 Surge）

### 5. Loon（付费）
**特点**：规则强大，支持脚本。  
**下载地址**： App Store（搜索 Loon）

### 6. SingBox（官方版）
**特点**：Sing-Box 官方 iOS 客户端，支持新协议，界面简洁，性能优秀，免费使用。  
**下载地址**： [SingBox App Store](https://apps.apple.com/app/sing-box-vt/id667373311684)

### 7. Karing
**特点**：全平台同步节点，可作为 Singbox/Clash 前端，界面现代化。  
**下载地址**： [Karing App Store](https://apps.apple.com/app/karing/id6472431552)

### 8. Potatso Lite（免费）
**特点**：免费的 iOS 代理工具，基础功能免费，界面简洁。  
**下载地址**： [Potatso App Store](https://apps.apple.com/app/potatso/id1239860606)

### 9. Outline
**特点**：专注于隐私保护的代理工具，开源透明。  
**iOS 下载**： [Outline iOS](https://apps.apple.com/app/outline-app/id1356177741)  
**macOS 下载**： [Outline macOS](https://apps.apple.com/app/outline-secure-internet-access/id1356178125)

---

<span id="tutorial"></span>
## 使用教程

### 快速开始指南

1. **选择客户端**  
   根据你的设备平台选择合适的客户端。新手推荐 Hiddify Next 或 Clash Verge Rev。

2. **下载安装**  
   点击对应工具的 Releases 链接或 App Store 下载最新稳定版，按照提示完成安装。

3. **获取订阅链接**  
   从机场服务商处获取订阅链接，或使用免费节点进行测试。

4. **配置客户端**  
   导入订阅链接或手动添加节点。  
   设置代理规则（建议开启规则分流）。  
   启动代理服务。

5. **测试连接**  
   访问测试网站确认代理是否生效。  
   检查 IP 地址是否已变更。

### 进阶配置建议

- **规则分流**：建议开启规则分流，只让需要的网站走代理。  
- **自动更新**：开启订阅自动更新，保持节点信息最新。  
- **备份配置**：定期备份配置文件，避免意外丢失。  
- **多客户端**：可以在不同设备上安装多个客户端，互为备用。  
- **协议选择**：优先使用 VLESS + Reality、Hysteria2、TUIC v5 等新协议。

---

<span id="faq"></span>
## 常见问题

### Q1：哪个客户端最好用？
**A**：这取决于你的具体需求。  
- Windows：推荐 Clash Verge Rev 或 V2RayN  
- macOS：推荐 ClashX 或 Stash  
- Android：推荐 Hiddify Next 或 ClashMeta for Android  
- iOS：推荐 Shadowrocket 或 Quantumult X

### Q2：免费节点能用吗？
**A**：免费节点仅供测试使用，存在稳定性差、速度慢、安全性无法保证等问题。建议购买付费服务获得稳定体验。

### Q3：客户端安全吗？
**A**：本列表中的所有客户端都是开源项目，代码透明，可以查看源代码，社区监督维护，无恶意代码，定期更新修复漏洞。

### Q4：如何选择机场服务？
**A**：选择机场服务时要考虑节点数量和分布、带宽和速度、稳定性和在线率、客服支持、价格合理性。

### Q5：为什么连接不上？
**A**：常见原因包括节点信息过期、本地网络问题、防火墙拦截、客户端配置错误。建议检查配置或更换节点。

### Q6：订阅格式不兼容怎么办？
**A**：使用 subconverter 或 Hiddify Next 内置转换工具进行格式转换。

---

## 免责声明

- 本列表仅供技术交流和学习使用  
- 请遵守当地法律法规  
- 合理使用网络服务  
- 不建议用于非法用途  
- 使用免费节点请注意隐私安全

---

## 贡献指南

欢迎提交 Issue 和 PR，帮助我们完善这个列表：  
- 推荐新的客户端工具  
- 报告失效的下载链接  
- 补充使用教程和技巧  
- 提出改进建议

---

**最后更新**：2026年4月14日  
**项目地址**：https://github.com/maomao533/dingyue-tools/tree/main
