FF14 心動光譜 — 全新 HTML 版本

入口：index.html
圖片：images/角色key.png

這是重新撰寫的新版本，沒有修改上一版檔案。
首頁、四個答案按鈕、結果卡、加時賽對話框都直接寫在 HTML。
CSS 在 head 的 style 區塊；角色資料、題庫與互動程式在頁尾 script。
以 textContent 更新文字、img.src 更新圖片，沒有 Base64 圖片，也不以 innerHTML 組裝畫面。

上傳 GitHub Pages：將 index.html 和 images 資料夾一起放入發布目錄。
html2canvas 從 CDN 載入，分享圖片需要網路與正常載入的同站圖片。
圖片容器使用 object-fit: contain，可直接換成同名透明全身 PNG。
本版保留 24 題、每題 4 選項，每角色 8 次出場且 A/B/C/D 各 2 次。
最高票並列時，以匿名二選一逐輪決選；不影響原始雷達數值。

本資料夾可直接發布，不需執行建置指令。本次未代為公開發布。
