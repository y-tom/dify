# ゼロからわかるDifyの教科書
# Dify コミュニティ版 セットアップメモ

このメモは、Dify（オープンソース・コミュニティ版）をローカル環境で利用するための手順をまとめたものです。
Dockerを使用して実行する構成を前提としています。

---

## 初回
### 1. `.env` ファイルの作成
- ~/workspace/dify/dokerディレクトリに `.env` ファイルを作成。
- `env.example` ファイルの内容をコピーして `.env` に貼り付けて保存。

### 2. Docker起動
- ~/workspace/dify/dokerディレクトリでDocker起動。
- docker compose up -d

### 3. 初回アクセス
- 以下のURLにアクセスし、アカウントを作成する。
- http://localhost/install

---

## 2回目以降
### 1. Docker起動
- ~/workspace/dify/dokerディレクトリでDocker起動。
- docker compose up -d

### 2. 通常アクセス
- 以下のURLにアクセスする。
- http://localhost

```
