# Stella — Personal Site

一个复古拼贴 + 手写字体的深绿色个人网页。

Deep moss green + coral pink + cream — inspired by riso-print zines, editorial magazines, and hand-drawn scrapbooks.

## Live Demo

<!-- 部署到 GitHub Pages 后替换为你自己的链接 -->

## 本地预览

直接双击 `index.html` 即可在浏览器打开，无需任何依赖。

## 部署到 GitHub Pages

1. Fork 或 clone 本仓库
2. Repository → **Settings → Pages**
3. **Source** 选 `Deploy from a branch`
4. **Branch** 选 `main` / `/ (root)`
5. Save，1-2 分钟后访问 `https://<你的用户名>.github.io/<仓库名>`

## 自定义

### 修改文字

打开 `index.html`，直接编辑对应文本即可。

### 修改配色

打开 `style.css`，顶部 `:root` 里的 CSS 变量：

```css
:root {
  --moss:      #37452F;  /* 主背景色 */
  --moss-deep: #2A3524;  /* 次背景色 */
  --pink:      #E0446B;  /* 主强调色 */
  --pink-soft: #F5B4C8;  /* 副强调色 */
  --cream:     #F5F1E8;  /* 主文字色 */
  --rag:       #EFE3C4;  /* 暖米色 */
  --yellow:    #F5E86B;  /* 高亮 */
  --ink:       #1A1A1A;  /* 深色文字 */
}
```

### 替换图片

- `hero-face.jpg` — 首页头像（推荐 3:4 竖版）
- `say-hi-illustration.png` — 联系区插画（透明底 PNG）

## 结构

```
stella-portfolio/
├── index.html                  # 页面结构
├── style.css                   # 样式
├── hero-face.jpg               # 头像
└── say-hi-illustration.png     # 联系区插画
```

## 设计参考

- Jean Jullien 手绘插画
- Matisse 剪纸拼贴
- 独立杂志编辑排版
- 复古 Riso 印刷

## License

MIT
