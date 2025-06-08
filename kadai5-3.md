## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイント:http://zipcloud.ibsnet.co.jp/api/search
* 機能:指定した郵便番号に対応する住所を返す
* リクエストとレスポンスのフォーマット
* {"message":null,"results":[{"address1":"東京都","address2":"千代田区","address3":"千代田","kana1":"ﾄｳｷｮｳﾄ","kana2":"ﾁﾖﾀﾞｸ","kana3":"ﾁﾖﾀﾞ","prefcode":"13","zipcode":"1000001"}],"status":200}
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* 名称: OpenWeatherMap API
* 参照URL: https://openweathermap.org/api
* エンドポイントと機能
* エンドポイント:https://api.openweathermap.org/data/2.5/weather
* 機能:指定した都市名に対応する天気情報を返す
* リクエストとレスポンスのフォーマット
* {"weather":[{"main":"Clear","description":"晴天"}],"main":{"temp":26.5,"humidity":52,"pressure":1012},"wind":{"speed":3.1},"name":"Tokyo"}
### Q3-3. 感想
* 今回の課題で苦労したこと
* APIのパラメータの指定やキーの取得方法を調べたりする作業に苦労した
* 演習を通して理解できたこと
* JSON形式のデータの扱い方が理解できた
* Web APIの利便性や課題など
* リアルタイムのデータなどを簡単に利用できるのは便利だと感じた。
* そして、ネットワークの障害が起きた際の対処などが課題として挙げられるのではないかと考えた。
