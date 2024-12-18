# お問い合わせフォーム 画面仕様書

## 1. 概要

本画面はユーザーからの問い合わせを受け付けるためのWebフォームです。

## 2. 画面レイアウト

### 2.1 全体構成
- 最大幅: 600px
- 背景色: 白色
- 外枠: 角丸(8px)、影付き
- 内部パディング: 30px

### 2.2 ヘッダー
- タイトル: 「お問い合わせフォーム」（中央寄せ）
- フォントカラー: #333

## 3. 入力項目

### 3.1 お名前
- 必須項目
- 入力形式: テキスト
- 入力欄幅: 100%

### 3.2 メールアドレス
- 必須項目
- 入力形式: email
- 入力欄幅: 100%
- バリデーション: メールアドレス形式

### 3.3 電話番号
- 任意項目
- 入力形式: テキスト
- 入力欄幅: 100%
- バリデーション: 数字とハイフンのみ許可

### 3.4 お問い合わせ種類
- 必須項目
- 入力形式: プルダウン選択
- 選択肢:
  1. 選択してください（初期値）
  2. 商品について
  3. サービスについて
  4. サポートについて
  5. その他

### 3.5 お問い合わせ内容
- 必須項目
- 入力形式: テキストエリア
- 入力欄高さ: 150px
- リサイズ: 垂直方向のみ可能

## 4. 送信ボタン

- 表示文言: 「送信する」
- 幅: 100%
- 背景色: #4CAF50
- ホバー時背景色: #45a049
- 文字色: 白
- パディング: 上下12px、左右24px

## 5. プライバシーポリシー表記

- 位置: フォーム最下部
- 文字サイズ: 14px
- 文字色: #666
- 表示文言: 「※ご入力いただいた個人情報は、お問い合わせへの対応のみに使用いたします。」

## 6. スタイル仕様

### 6.1 フォント
- フォントファミリー: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif
- 行間: 1.6

### 6.2 入力フィールド共通仕様
- 内部パディング: 8px
- ボーダー: 1px solid #ddd
- 角丸: 4px
- フォントサイズ: 16px

### 6.3 必須項目マーク
- 文字色: #ff4444
- 左マージン: 5px

## 7. フォーム送信仕様
- 送信メソッド: POST
- 送信先: /submit

## 8. レスポンシブ対応
- ビューポート設定あり
- コンテンツ幅は画面サイズに応じて自動調整
- 基本パディング: 20px
