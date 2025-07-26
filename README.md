# Aave-V2-protocol-credit-score-algorithm-by-Zeru

### Your Challenge

You are provided with sample 100K raw, transaction-level data from the Aave V2 protocol. Each record corresponds to a wallet interacting with the protocol through actions such as `deposit`, `borrow`, `repay`, `redeemunderlying`, and `liquidationcall`.

Your task is to develop a robust machine learning model that assigns a **credit score between 0 and 1000** to each wallet, based solely on historical transaction behavior. Higher scores indicate reliable and responsible usage; lower scores reflect risky, bot-like, or exploitative behavior.

Decide which features to engineer from DeFi transaction data
Implement a one-step script that generates wallet scores from a json file which contains the a small sample of user-transactions.
