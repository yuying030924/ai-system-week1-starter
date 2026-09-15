# Week 1 Evidence

學號：7115029057

姓名：詹于瑩

## Check-off

1. Dataset 在哪裡？

data/customer_intent_demo.csv

2. Baseline 程式在哪裡？

src/rule_baseline.py

3. 本週 Accuracy = 0.950

4. 請填寫一個 Failure Case：

   - 輸入訊息：退貨物流已收走但沒有更新
   - 正確答案：refund_return
   - Baseline 預測：order_delivery

5. 你覺得這個 Baseline 為什麼會錯？請用一句話說明。

   因為這個baseline或依照類別順序去判斷，所以當看到物流符合order_delivery時就直接回傳結果，沒有判斷到refund_return的部分

6. 這是否代表現在一定要使用 AI？為什麼？請用一句話說明。

   不一定，這個部分的錯誤其實可以先調整關鍵字的順序或加上明確的規則來解決。
