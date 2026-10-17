# 纯净直播（pure live）虎牙高画质修复版

## 作者与来源

本仓库基于 **[ljezio](https://github.com/ljezio)** 开发的 **[pure-live](https://github.com/ljezio/pure-live)**，增加虎牙高画质切换与播放器延迟初始化的兼容修复。

- **原作者：ljezio**。界面、多平台支持及基础功能来自原项目。
- [原项目与源代码](https://github.com/ljezio/pure-live) · [原作者的 ScriptCat 脚本](https://scriptcat.org/zh-CN/script-show-page/4481)
- 虎牙修复与维护：**[yt0575](https://github.com/yt0575)**。
- 许可证：**GPL-3.0-or-later**，保留原作者署名及版权信息。

## 修复版下载

- [ScriptCat：纯净直播（pure live）虎牙高画质修复版](https://scriptcat.org/zh-CN/script-show-page/8539)
- [GitHub Release v5.2.15：完整用户脚本与校验文件](https://github.com/yt0575/pure-live/releases/tag/v5.2.15)

ScriptCat 发行版仅调整名称、命名空间、介绍与来源署名，运行代码与 v5.2.15 Release 保持一致。安装后只启用原版或修复版中的一份，避免重复执行。

## 原项目介绍与入口

[![License](https://img.shields.io/github/license/ljezio/pure-live)](https://spdx.org/licenses/GPL-3.0-or-later.html)
[![GitHub](https://img.shields.io/badge/GitHub-pure_live-blue?logo=github)](https://github.com/ljezio/pure-live)
[![GreasyFork](https://img.shields.io/greasyfork/dt/533987?label=GreasyFork&logo=greasyfork)](https://greasyfork.org/zh-CN/scripts/533987)
[![ScriptCat](https://img.shields.io/badge/dynamic/json?label=ScriptCat&color=1296dc&url=https://scriptcat.org/api/v2/scripts/4481&query=%24.data.total_install&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACYAAAAmCAYAAACoPemuAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAAGdYAABnWARjRyu0AAARNSURBVFhH7Vfba1xFHN5WwQtmd3%2B%2FOQWLpa0g0mcFb0%2FtXyCCz6LiBfHFQpteEFZERIUIaXZmztlLsia2io%2F64g19sbVFQVtD2505e85mk82ladLa1UL6MvI7m4bsnGyTmpMikg8%2BssyZ%2Bb6PnDm%2F%2BU0qtYn%2FLXI%2F3p3NVz9kQ9MnsRC%2BxUoXeuwp6wX2n06jF%2B4nj2y%2B%2BkHqC3OXPScGPFZ9glVmDPtk1jjDlw26YQAyOJAR58Cee7vIiDEA4R9ELwxImzxYZdo4wn%2FcnhsDcP0MK4wZlDWDQhtWmjCMAnr1Orj1g%2Bm%2BUbTXrIZ0cRTBC3rRG6uTFmmSNnmwQt2gUE%2FZa2LIFOoPg1DX0aMFeomsNG7Y8JwBNxxnhfFDawlIc1hx7DB4wQStJY3lmuQBXP2dkeFue20MtKdA6ClWbHSKLAvoUECvPp7l%2BkjPwPlHsV%2FtAK%2B2k0i%2FozGhj9IcmsuKVqCbWsUGBZvclh99wM4RhzFbUKhzrNyMCdkBWeUSCS%2BA0C0Q%2Bq9FtoDrBXrWLdCSRtvj91TKbLFjrAjg6js2NBMTWpFeGL2STobxeSuQPEDob2z%2FrgCuhumLsYWSJnkA1xXbvytAqPfvWDCh3rP9u4IJ%2FeadCpYV6g3bvytQ%2Bs%2BxwSmD0o%2BJJUbpG%2FJgUj9r%2B3cFDOinow28WGQ3hG7NoBsYzAdP2v5dQUUWubqx1q%2FrX5G0uVpYU3G9icxQmAWupllh5SKbBKPiKtQUeLWM7X9LIFd%2FrFZk10NWnqS%2FZ23frqCW5JF%2BdQ%2Fw6rdsaDommBSjAs7V17ty4b2YO522c3QApH4VS80p5LoGQl%2BKNucKoonQDeg4myEv8gRx8RU7Txu53FYUquGcuNZuS6KNr%2BKCSZGryIO8nBMt8qrTOW3HigBSv8sGJ2%2FQK4y6C1psCyZFriIPeqXkCVK%2FY%2BfpAPPCPShrz6PwT7LSBm7%2BtvZP5MWOXdxj5%2BgKFP7bbGQ%2BJpgUF7WP2r6rAvPq5Y08L1ll1mDef9H2XRU9A%2BcZSL9lt9iJkFpq6V9bS3u%2BBOw%2Fu4O54T6Q%2FutUmaOLiS28TpImtdTgBq8xV%2B9DWX3IztGBLK%2B%2BwMqTV6KbUWVmYw9xuiHRNZG8ys0rmFf77TxLQKF%2Fcz6%2F3v6MqSWhex8xOpqSKB0q0lrSJY9iwziftah8hF17f%2BTqJSw351Doyyhrp1DoEeCqF4T6IbpbivX0Z350PwWhvwepepHrT0H6PwPXs6w08Sfj6pCdpwPbPhp9MF1sdGzK7d6v96MbfOUcv9ouvDHTWzP6rxy%2FShv%2By1TfqfuWa6f7Guh8%2FMv25WO3h5zZCm5A1%2Ft5Z2SeqnX72KLzlDrd5aQxOm4GpwzNRS%2BcAy84QMeeLZsYMvLCbvTCI%2BCGZ8ANWlGLTPumPLnIZhSOnoEbnGFeeDibD3bZOhsK8Jo7nQH9GJN6L332EaXeS2P0zJ6%2FiU38l%2FAPHnCGwbDU2eAAAAAASUVORK5CYII%3D)](https://scriptcat.org/zh-CN/script-show-page/4481)

**🤩移除一切花里胡哨的东西，只保留直播和弹幕**

- 自动网页全屏，双击全屏
- Enter键弹出弹幕输入框
- 自动切换最高画质
- 一键关闭脚本

### 🦈斗鱼（douyu）

### 🐯虎牙（huya）

- 自动关闭直播间贴片广告
- 去除扫码解锁清晰度限制

### 📺B站直播（bilibili）

### 🎶抖音直播（douyin）
