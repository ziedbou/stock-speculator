# Stock-speculator solver
You are given an array of prices where prices[i] is the price of a given stock on the ith day.
You work for a stock speculator. You want to maximize your employer's profit by helping her choose a single day to buy one stock and a different day in the future to sell it.
Write a function that returns the day on which to buy, the day on which to sell, and the maximum profit you can achieve from this transaction.

## Example given data :
``` javascript
let data = [190, 59, 69, 60, 360, 140, 535, 695, 700, 40, 500, 590, 600, 650]
```
## Response 
``` javascript
{
  "days": [
    {
      "buy_day_index": "1",
      "sell_day_index": "2",
      "profit_value": 10
    },
    {
      "buy_day_index": "3",
      "sell_day_index": "4",
      "profit_value": 300
    },
    {
      "buy_day_index": "5",
      "sell_day_index": "8",
      "profit_value": 560
    },
    {
      "buy_day_index": "9",
      "sell_day_index": "13",
      "profit_value": 610
    }
  ],
  "total_profit": 1480
}
```
