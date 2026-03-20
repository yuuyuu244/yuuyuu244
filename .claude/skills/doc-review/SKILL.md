---
name: doc-review
description: ドキュメントレビューを行う
metadata:
    author: Yuki-Kikuya
    version: 1.0.0
    tags:
        - langage=ja,en
---

# ドキュメントレビュー

- [ ] 日本語の文法が正しく用いられているか
- [ ] 英語の文法が正しく用いられているか
- [ ] 読者にとって読みやすい文章・構造・順序になっているか

## 注意事項

- ドキュメントを変更した場合は必ず `mise run lint` を実行してください

## Optional

- `-t, --target` : 対象ファイル (Default: `*.md`)
