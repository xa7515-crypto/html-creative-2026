# 2026html創作學習（專案藍圖）

> 本檔為跨 Agent 通用的專案藍圖（AGENTS.md 開放標準）。任何 Agent 的每個 session 都應先讀本檔＋`handoff.md`。

## 專案簡介
以 HTML/CSS/JS 製作教學用網頁教材（給學生用的互動網頁、複習網站）為目標的創作學習專案。

## 關鍵時程
<!-- 目前無明確時程，之後有再補 -->
- （留白）

## 目標與路線圖
- [ ] 階段一：HTML/CSS/JS 基礎學習與小作品練習
- [ ] 階段二：完成一份可上線的教學用網頁教材

## 資料夾結構
<!-- 2026-10-14 初始化時掃描生成；2026-10-14 匯入朋友 lesson-prep-public 純前端站台並改為新趨勢老師品牌 -->
- `AGENTS.md` — 專案藍圖（本檔）
- `handoff.md` — 交接檔（開工必讀、收工必更新）
- `index.html`、`styles.css`、`script.js` — 國語備課站台（新趨勢老師品牌，原作者 sunny680228）
- `public-data.js`、`learning-focus-data.js` — 教材索引與學習重點資料
- `interactive-generator/` — 互動教材提示詞產生器（新趨勢老師品牌，原作者 sunny680228）
- `math-demo/` — 數學四上互動學習入口範例（新趨勢老師品牌，原作者 sunny680228）
- `math4-01/`～`math4-06/`、`math4-09/` — 7 個數學單元互動頁（新趨勢老師品牌，原作者 sunny680228）
- `math4-07/`、`math4-08/`、`math4-10/` — 3 個數學單元互動頁（使用者自製，新趨勢老師品牌）
- `math-units-links.csv` — 試算表匯入檔（單元＋連結，B 欄為 Pages 預定網址，開通後生效）
- `assets/` — 頭像等素材（`my-avatar.jpg` 新趨勢老師頭像）
- `.nojekyll` — GitHub Pages 設定
- `.git/` — Git 版本控制（L2：GitHub 私有 repo）

## 同步層級（本專案初始化至第 3 層級）

| 層級 | 平台 | 位置 | 讀取時機 |
|------|------|------|---------|
| L1 | 本地（雲端硬碟資料夾） | `AGENTS.md`＋`handoff.md` | 每個 session |
| L2 | GitHub | xa7515-crypto/html-creative-2026（公開，上線：https://xa7515-crypto.github.io/html-creative-2026/） | 指定時 |
| L3 | Obsidian | 2026html創作學習/專案工作流程.md | 有需要時 |

## 工作約定
- 任何 Agent、任何電腦：**開工先讀 `handoff.md`，收工必更新 `handoff.md`**
- 修改共用檔案前先讀最新內容，避免覆蓋其他 Agent 的變更
- 所有回應與文件使用繁體中文
- 修改前先確認計畫，優先保留原有資料結構

## 安全與隱私（不可違反）
- **不把 API key、密碼、憑證寫進 repo**，也不要貼進 `AGENTS.md`／`handoff.md`；一律放 `.env` 並列入 `.gitignore`
- **學生資料只用座號**，不出現姓名、學號、班級以外的個資、照片或聯絡方式
- 要公開分享前，先確認檔案裡沒有上述兩類內容
