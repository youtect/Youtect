# YOU TECT corporate site

静的サイトです。公開時は GitHub リポジトリにこのフォルダの内容を push し、Netlify でリポジトリを接続してください。ビルドコマンドは不要で、公開ディレクトリは `dist` です（`netlify.toml` 設定済み）。

## ローカル確認

任意の静的 HTTP サーバーで `dist` を公開してください。例：

```powershell
npx serve dist
```

公開前に以下を差し替えてください。

- 会社所在地・正式な連絡先
- `info@youtect.jp` の実運用開始後の問い合わせ導線
- 取扱保険会社表記・必要な募集文書/法定表記
