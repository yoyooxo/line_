# LINE 帳號防盜手冊

防詐宣導教材，單一 HTML 檔案，不需要後端、不需要安裝任何東西。

- `index.html` — 網站本體（含所有樣式、圖示與互動程式）
- 外部只載入 Google Fonts 字型，其餘全部內嵌

## 發佈到 GitHub Pages

1. 在 GitHub 新開一個 repository（Public）
2. 在這個資料夾執行：

   ```
   git init
   git add .
   git commit -m "LINE 帳號防盜手冊"
   git branch -M main
   git remote add origin https://github.com/<你的帳號>/<repo 名稱>.git
   git push -u origin main
   ```

3. 到 repo 的 Settings → Pages → Source 選 `Deploy from a branch`，
   Branch 選 `main` / `(root)`，按 Save
4. 等一兩分鐘，網址會是 `https://<你的帳號>.github.io/<repo 名稱>/`

## 本機預覽

直接用瀏覽器打開 `index.html` 即可。

## 授權

防詐內容歡迎自由使用。
