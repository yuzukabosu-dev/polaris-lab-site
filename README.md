# polaris-lab-site
# Polaris Lab

SAPフリーランス × AI駆動のLP制作。ビジネスの成果につながるサイトをスピーディに届けます。

🔗 **公開URL：** https://your-username.github.io/your-repo-name/

> ⚠️ 上記URLは仮のものです。GitHub Pagesで公開後、実際のURLに書き換えてください（書き換え方は本ファイル末尾を参照）。

---

## 📌 概要

**Polaris Lab** は、SAPフリーランスとして10年超の実績を持つ個人事業主が運営する、LP（ランディングページ）制作のポートフォリオサイトです。

本業のSAPコンサルティングで培った「ビジネスの数字を動かす」視点と、Claude・ChatGPT などのAIを最大限に活用した制作スピードを掛け合わせ、**成果につながるLPをリーズナブルに提供**することを目指しています。

現在はポートフォリオ構築中のフェーズで、サンプル作品を中心に掲載しています。

---

## 🛠 提供サービス

| サービス | 内容 |
|---|---|
| **LP制作** | 集客・販売・問い合わせ獲得を目的としたランディングページの新規制作 |
| **LPデザイン・コーディング** | HTML/CSS/JavaScriptによるレスポンシブ対応のコーディング |
| **コピーライティング** | ファーストビューのキャッチコピーからCTA設計まで一括対応 |
| **AI活用での高速制作** | AIツールを駆使し、最短数日でのスピード納品が可能 |
| **無料相談・見積もり** | 制作前のヒアリング・お見積もりは無料 |

---

## 💻 使用技術

### フロントエンド
- **HTML5** — セマンティックなマークアップ
- **CSS3** — Flexbox / Grid によるレスポンシブレイアウト、CSS変数によるテーマ管理
- **JavaScript（Vanilla JS）** — フレームワーク非依存。軽量・高速な動作を重視

### 主な機能・実装
- スクロール連動アニメーション（Intersection Observer API）
- モーダルウィンドウ（Worksカードのクリックで詳細表示）
- フォームバリデーション（リアルタイムエラー表示）
- モバイル対応ハンバーガーメニュー
- アクセシビリティ対応（`aria-*` 属性、キーボード操作、`prefers-reduced-motion` 対応）

### フォント
- [Google Fonts](https://fonts.google.com/) — Noto Sans JP / DM Sans

### 開発・運用
- **Git / GitHub** — バージョン管理
- **GitHub Pages** — 静的サイトホスティング
- 外部ライブラリ・ビルドツール不使用（単一HTMLファイルで完結）

---

## 🚀 GitHub Pages 公開手順

このサイトは静的HTMLのみで構成されているため、GitHub Pagesに無料で公開できます。

1. GitHubで新しいリポジトリを作成する
2. `portfolio.html` を `index.html` にリネームしてリポジトリのルートにアップロード
   ```bash
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/ユーザー名/リポジトリ名.git
   git push -u origin main
   ```
3. リポジトリの **Settings** → **Pages** を開く
4. **Source** を `Deploy from a branch`、**Branch** を `main` / `/(root)` に設定して保存
5. 数分後、以下のURLで公開される
   ```
   https://ユーザー名.github.io/リポジトリ名/
   ```
6. 公開できたら、本READMEの先頭にある **公開URL** を実際のURLに書き換える

---

## 📂 ファイル構成

```
.
├── index.html      # メインページ（HTML/CSS/JS を含む単一ファイル）
└── README.md       # このファイル
```

---

## 📬 お問い合わせ

サイト内の「Contact」セクションのフォームより、LP制作のご依頼・お見積もり・ご相談を受け付けています。

© 2026 Polaris Lab. All rights reserved.
