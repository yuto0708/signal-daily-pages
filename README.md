# Public Pages Site

このフォルダは、公開専用の GitHub Pages リポジトリへ移すための最小セットです。

入っているもの:

- `index.html`
- `launch-summary.html`
- `business-plan.html`
- `launch-complete-plan.html`
- `.nojekyll`

入っていないもの:

- Discord / Notion / GitHub Actions の自動配信コード
- `.agents/`
- 秘密情報や API キー
- 非公開運用用の設定

使い方:

1. 新しい Public リポジトリを GitHub で作る
2. このフォルダの中身だけを新しいリポジトリに入れる
3. GitHub Pages を `GitHub Actions` か `Deploy from a branch` で有効化する

このフォルダ自体は、元の非公開リポジトリの運用には影響しません。
