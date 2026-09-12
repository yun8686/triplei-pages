# triplei-pages

triplei名義で公開するアプリの静的ページ（プライバシーポリシー・サポート案内など）を
GitHub Pagesでホスティングするためのリポジトリ。

アプリごとにファイルをキャメルケースのアプリ名で分け、フラットに配置する
（例: `break100AiCoach.html` / `break100AiCoachSupport.html`）。
新しいアプリを追加する場合は同じ命名規則でファイルを追加し、`index.html`にリンクを足す。

## 公開ページ

- [Break100 AI Coach プライバシーポリシー](https://yun8686.github.io/triplei-pages/break100AiCoach.html)
- [Break100 AI Coach サポート](https://yun8686.github.io/triplei-pages/break100AiCoachSupport.html)
- [カタチ合わせ（Shape Match） プライバシーポリシー](https://yun8686.github.io/triplei-pages/shapePuzzle.html)
- [カタチ合わせ（Shape Match） サポート](https://yun8686.github.io/triplei-pages/shapePuzzleSupport.html)
- [Queensソルバー（Queens Solver） プライバシーポリシー](https://yun8686.github.io/triplei-pages/queensSolver.html)
- [Queensソルバー（Queens Solver） サポート](https://yun8686.github.io/triplei-pages/queensSolverSupport.html)

ソースは各アプリのリポジトリ側にもある（例: Break100 AI Coachは
`break100_ai_coach/release/privacy_policy/`、カタチ合わせは
`shape_puzzle/release/privacy_policy/`、Queensソルバーは
`queen-puzzle-solver/docs/`）。内容を更新する場合は
元のアプリリポジトリ側を先に直し、このリポジトリへコピーする。
