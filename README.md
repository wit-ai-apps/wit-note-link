# PROJECT: wit-note-link

## 概要
- 目的：ノート作成／書き込み（ペン・マーカー）／消しゴム／A4実寸表示／PDF出力など
- 形態：Web（単一HTML）＋（必要なら）GAS連携

## 重要リンク（あとで埋める）
- GitHub（正本）：https://github.com/wit-ai-apps/wit-note-link
- 配布URL（必ず ?b=BUILD_ID）：
- 仕様メモ（AIBRAIN/Drive等）：
- 既知の重要ルール（UI凍結など）：

## UI凍結ルール（最重要）
- UI（見た目）は完全固定（変更禁止）
  - HTML構造 / 文言 / 配置 / サイズ / 色 / 余白 / クラス名
- 変更してよいのは「内部処理（ロジック）」のみ
- UI差分が出たら **差し戻し優先**

## 依頼文の固定フレーズ（Rex/Gemini/ユイ共通）
依頼の先頭に必ず書く：
> UI凍結で、中身だけ。UI差分が出たら差し戻し。

## 版管理ルール（固定）
- VERSION：vX.Y.Z
- BUILD_ID：YYYY-MM-DD_HHMM_<tag>
- 配布URL：必ず `?b=BUILD_ID`（検証のみ `&debug=1`）
