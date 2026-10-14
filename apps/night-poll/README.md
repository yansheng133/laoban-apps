# night-poll

此目錄由 laoban 產生，請勿手動修改；要變更請在 laoban 頁面的應用清單按「編輯」。

## 這次的需求（已遮蔽）

> （user-kgw7z）結果頁加上「重新整理」按鈕；（user-kgw7z）［vote_api.py］回傳票數時順便回傳百分比；（user-kgw7z）［vote-form.html］投票按鈕放大一些；（laoban-cli-test）［vote-form.html］表單送出後清空欄位；（laoban-cli-test）［night-poll-api］API 加上投票截止時間；（laoban-cli-test）一般意見：整體配色更清楚

## 計畫摘要

> 一個簡易投票工具，允許使用者建立投票題目與選項，進行投票並即時查看結果長條圖。系統限制每個人只能投一次票。新增投票截止時間功能，並改善前端UI與結果顯示。

## 產生資訊

- 產生時間：2026-10-14T16:05:30Z
- 模型：`qwen3-coder:30b`
- 部署目標 namespace：`laoban-dev`
- 映像：`registry.suse.com/bci/python:3.13`
