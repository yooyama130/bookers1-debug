# README

●ActiveRecord::PendingMigrationErrorの対応
　→rails db:migrate:statusでマイグレート状況を確認してみる

●Load Errorの対応
　→定数HomesControllerの自動ロードができず、homes_controller.rbで定義する必要がある＝ 「homescontroller」で定義されていない。

●マイグレートのリセット方法
　一つ前まで戻す
　　$ rails db:rollback
　x個前までファイルを戻す
　　$ rails db:rollback STEP=x

●render後のページに@booksが必要。