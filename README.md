# 给尤家瑜的生日信

《星光木语 · 游乐园》—— 一封要在浏览器里拆开的生日信。

- 在线地址：https://yikl66.github.io/jia-yu-letter/
- 打开后输入密码 `you`，就可以进信了。
- 进度会自己往下走：信纸 → 卷轴 → 火柴蛋糕 → 吹蜡烛 → 文字页 → 20 颗星 → 游乐园 → 接电话。

## 这个仓库里是什么

`index.html` 是信本体（约 150 KB），`assets/` 下是四段大体积音频与场景数据的分片：

| 文件 | 内容 |
| --- | --- |
| `assets/BGM_B64.*.js` | 背景音乐 Sweet (feat. Landon Sears) |
| `assets/PHONE_B64.*.js` | 3D 翻盖机（接电话那一幕） |
| `assets/PARK_B64.*.js` | 游乐园沙盘 |
| `assets/VOICE_B64.*.js` | 本人录的那条语音 |

这些数据原本整段 base64 内嵌在单个 HTML 里（那样双击就能用 file:// 打开），
这里拆成分片单独放，是为了能整份传到 GitHub Pages。信的行为跟单文件版完全一样。