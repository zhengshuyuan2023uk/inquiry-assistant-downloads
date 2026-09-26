# 询盘助手下载

公开提供试用安装套件。适用于 Apple 芯片 Mac（含 M4），要求 macOS 14 或以上；首次安装由实施人员协助。

**查看或二次开发源码：** [询盘助手开源项目](https://github.com/zhengshuyuan2023uk/inquiry-assistant)。源码、测试、合成演示和构建说明在独立仓库，自有代码采用 MIT；业务员安装继续使用本页的成品套件。

## 下载安装套件

**[打开安装套件下载页](https://github.com/zhengshuyuan2023uk/inquiry-assistant-downloads/releases)**

在版本页面的 **Assets（资源）** 中选择 `inquiry-assistant-…-macos-arm64-….zip`，约 185 MB。不要选择 GitHub 自动生成的 `Source code (zip)`：它只有此下载页的资料，不是安装套件。

下载后解压，按编号操作：

1. `01-现场安装.command`：建立企业工作区；缺少 Python 时先安装随包运行环境，再重新打开此入口。
2. `02-连接AI.command`：客户登录自己的 AI 账号。
3. `03-连接WhatsApp.command`：客户使用手机扫码。
4. `04-打开工作台.command`：选择客户、更新聊天、补充企业资料。
5. `05-检查安装.command`：检查状态，再完成真实新消息、回复和重启验收。

业务员日常双击桌面的 **打开询盘助手**。首次安装由实施人员协助。

[阅读完整现场安装手册](MAC_ONSITE.md) · [组件来源](MAC_COMPONENTS.md) · [校验值](SHA256SUMS.txt)

## 下载与数据

这是公开下载仓库，下载不需要 GitHub 账号或仓库邀请。请勿在这里上传客户聊天、企业报价、账号登录文件或密钥。首次安装仍需客户自行完成 AI 登录与 WhatsApp 扫码。

## 当前交付范围

支持客户选择、手动更新聊天、AI 回复、个性化调整、润色、企业知识与回复策略。回复由业务员检查后手动发送。

本版为企业试用部署包，含本地程序源文件及必要第三方组件，不包含任何开发者账号、客户聊天或登录。未提供 Windows 原生支持、多人权限、自动发送或自动更新。Mac 系统可能要求确认运行下载的软件；套件整体尚未完成 Apple 开发者签名、公证。

各版本保留对应的校验值和说明。产品自有代码的 [MIT 许可](https://github.com/zhengshuyuan2023uk/inquiry-assistant/blob/main/LICENSE)与[第三方范围说明](https://github.com/zhengshuyuan2023uk/inquiry-assistant/blob/main/THIRD_PARTY_NOTICES.md)见源码仓库；各第三方组件继续保留随包许可，整个安装包不统一标为纯 MIT。
