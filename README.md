# AnimalClock Privacy Policy

本仓库仅托管 iOS / watchOS 应用 **动物闹铃（AnimalClock）**（Bundle ID: `com.animalclock.app`）的隐私政策静态页，用于 App Store Connect 的 **Privacy Policy URL**。

## 页面地址（开启 GitHub Pages 后）

将 `YOUR_GITHUB_USERNAME` 换成你的 GitHub 用户名，仓库名若不同请一并替换：

```text
https://YOUR_GITHUB_USERNAME.github.io/animalclock-privacy/
```

建议仓库名：`animalclock-privacy`（与上方路径一致时最省事）。

## 文件

| 文件         | 说明                     |
| ------------ | ------------------------ |
| `index.html` | 隐私政策正文（中英双语） |
| `README.md`  | 本说明                   |

## 发布步骤（简要）

1. 用新 GitHub 账号新建 **Public** 仓库（例如 `animalclock-privacy`）。
2. 上传本目录中的 `index.html` 与 `README.md`。
3. 仓库 **Settings → Pages**：
   - Source：Deploy from a branch
   - Branch：`main`（或 `master`）+ `/ (root)`
   - Save
4. 等待 1～2 分钟，用无痕窗口打开上方 `github.io` 链接确认可访问。
5. 把该链接填到 App Store Connect → App 隐私政策 URL。

## 提交前请修改

在 `index.html` 中全局替换：

- `YOUR_EMAIL@example.com` → 你的真实支持邮箱（需与商店联系信息一致或可回复）

如有产品更名、新增分析 SDK、云同步或账号系统，请同步更新 `index.html` 并提高页内生效日期。

## 本政策已覆盖的产品行为（摘要）

- 无账号体系；闹铃等内容主要存本机（含 App Group，供 Widget / Watch 使用）
- 麦克风：自定义录音，本地保存，不上传到开发者服务器
- 选图：系统 PhotosPicker，不申请完整相册权限
- VIP：Apple 内购 / StoreKit
- 网络：可能请求公共节假日等公开数据源（第三方可能看到 IP 与国家代码）
- 无第三方广告 SDK / 无 ATT 跨 App 追踪广告

## License

本仓库文档以提供隐私披露为目的发布；应用本身的代码与资源权利归开发者所有。
