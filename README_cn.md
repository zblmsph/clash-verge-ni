<h1 align="center">
  <img src="./src/assets/image/logo.png" alt="Clash" width="128" />
  <br>
  Clash Verge
  <br>
</h1>

<h3 align="center">
基于 <a href="https://github.com/tauri-apps/tauri">tauri</a> 的 <a href="https://github.com/Dreamacro/clash">Clash</a> 图形用户界面。
</h3>

## 安装

从 [release](https://github.com/zzzgydi/clash-verge/releases) 下载。支持 Windows x64、Linux x86_64 和 macOS 11+

- [Windows x64](https://github.com/zzzgydi/clash-verge/releases/download/v1.3.8/Clash.Verge_1.3.8_x64_en-US.msi)
- [macOS intel](https://github.com/zzzgydi/clash-verge/releases/download/v1.3.8/Clash.Verge_1.3.8_x64.dmg)
- [macOS arm](https://github.com/zzzgydi/clash-verge/releases/download/v1.3.8/Clash.Verge_1.3.8_aarch64.dmg)
- [Linux AppImage](https://github.com/zzzgydi/clash-verge/releases/download/v1.3.8/clash-verge_1.3.8_amd64.AppImage)
- [Linux deb](https://github.com/zzzgydi/clash-verge/releases/download/v1.3.8/clash-verge_1.3.8_amd64.deb)
- [Fedora Linux](https://github.com/zzzgydi/clash-verge/issues/352)

或者您可以自行构建。支持 Windows、Linux 和 macOS 10.15+

注意：如果您在 Windows 上无法启动应用程序，请检查您是否已安装 [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)。

### 常见问题

#### 1. **macOS** "Clash Verge" 已损坏，无法打开

打开终端并运行 `sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app`

## Development
您应该安装 Rust 和 Nodejs(请参阅[此处](https://tauri.app/v1/guides/getting-started/prerequisites/)了解更多详细信息.)

安装 Nodejs 包。
```shell
yarn install
```
然后下载 clash 二进制文件

```shell
# force update to latest version
# yarn run check --force

yarn run check
```
运行

```shell
yarn dev

# run it in another way if app instance exists
yarn dev:diff
```

或者直接构建

```shell
yarn build
```
## 截图

<div align="center">
  <img src="./docs/demo1.png" alt="demo1" width="32%" />
  <img src="./docs/demo2.png" alt="demo2" width="32%" />
  <img src="./docs/demo3.png" alt="demo3" width="32%" />
  <img src="./docs/demo4.png" alt="demo4" width="32%" />
  <img src="./docs/demo5.png" alt="demo5" width="32%" />
  <img src="./docs/demo6.png" alt="demo6" width="32%" />
</div>

## 可自定义主题色彩

<div align="center">
  <img src="./docs/color1.png" alt="demo1" width="16%" />
  <img src="./docs/color2.png" alt="demo2" width="16%" />
  <img src="./docs/color3.png" alt="demo3" width="16%" />
  <img src="./docs/color4.png" alt="demo4" width="16%" />
  <img src="./docs/color5.png" alt="demo5" width="16%" />
  <img src="./docs/color6.png" alt="demo6" width="16%" />
</div>

## 免责声明
这是一个rust语言学习项目

## 致谢

Clash Verge 基于或受到这些项目的启发等等：

- [tauri-apps/tauri](https://github.com/tauri-apps/tauri)：使用 Web 前端构建更小、更快、更安全的桌面应用程序。
- [MetaCubeX/Clash.Meta](https://github.com/MetaCubeX/Clash.Meta)：Go 中基于规则的隧道。
- [Fndroid/clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg)：基于 Clash 的 Windows/macOS GUI。
- [vitejs/vite](https://github.com/vitejs/vite)：下一代前端工具。速度很快！

## 协议
GPL-3.0 协议。详情请参阅此处 [License here](./LICENSE)
