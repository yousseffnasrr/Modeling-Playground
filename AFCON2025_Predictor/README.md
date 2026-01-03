⚽ 𝐓𝐡𝐞 𝐀𝐅𝐂𝐎𝐍 𝟐𝟎𝟐𝟓 𝐛𝐫𝐚𝐜𝐤𝐞𝐭 𝐢𝐬 𝐬𝐞𝐭. 𝐁𝐮𝐭 𝐰𝐡𝐨 𝐚𝐜𝐭𝐮𝐚𝐥𝐥𝐲 𝐥𝐢𝐟𝐭𝐬 𝐭𝐡𝐞 𝐭𝐫𝐨𝐩𝐡𝐲 𝐢𝐧 𝐌𝐨𝐫𝐨𝐜𝐜𝐨?

Football is played on grass, but sometimes the best insights come from the data. Instead of relying on gut feelings, I built a 𝐩𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐯𝐞 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐦𝐨𝐝𝐞𝐥 to simulate the entire road 𝐟𝐫𝐨𝐦 𝐭𝐡𝐞 𝐫𝐨𝐮𝐧𝐝 𝐨𝐟 𝟏𝟔 𝐭𝐨 𝐭𝐡𝐞 𝐟𝐢𝐧𝐚𝐥.

Here is how I approached it from a Data Science perspective:

📊 𝐓𝐡𝐞 𝐃𝐚𝐭𝐚:

I leveraged a comprehensive International Football dataset from Kaggle (updated daily), capturing decades of match results to ensure the model understands historical context, not just recent hype.

⚙️ 𝐓𝐡𝐞 𝐌𝐨𝐝𝐞𝐥:

I chose a 𝐑𝐚𝐧𝐝𝐨𝐦 𝐅𝐨𝐫𝐞𝐬𝐭 𝐂𝐥𝐚𝐬𝐬𝐢𝐟𝐢𝐞𝐫 for this task.

Why? Because football is chaotic and non-linear. A simple regression can't capture why an underdog upsets a giant, but a "Forest" of decision trees can isolate the complex patterns that lead to those wins.

🧪 𝐓𝐡𝐞 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬:

I developed a set of predictive indicators to capture the 𝐜𝐫𝐢𝐭𝐢𝐜𝐚𝐥 𝐝𝐞𝐭𝐞𝐫𝐦𝐢𝐧𝐚𝐧𝐭𝐬 of victory in a high-stakes tournament:

𝟏. 𝐖𝐞𝐢𝐠𝐡𝐭𝐞𝐝 𝐑𝐞𝐜𝐞𝐧𝐭 𝐅𝐨𝐫𝐦: Because how you played last week matters more than how you played last year.

𝟐. 𝐓𝐡𝐞 𝐇𝐨𝐬𝐭 𝐅𝐚𝐜𝐭𝐨𝐫: I built a custom weighting logic to account for Home Advantage (specifically for Morocco) and regional advantages for North African neighbors (Egypt, Tunisia, Algeria).

𝟑. 𝐇𝐞𝐚𝐝-𝐭𝐨-𝐇𝐞𝐚𝐝 𝐇𝐢𝐬𝐭𝐨𝐫𝐲: Analyzing specific rivalries (only from 2020 onwards) to catch "mental blocks" between teams.

𝟒. 𝐅𝐈𝐅𝐀 𝐑𝐚𝐧𝐤𝐢𝐧𝐠𝐬: A baseline measure of squad quality.


🏆 𝐓𝐡𝐞 𝐑𝐞𝐬𝐮𝐥𝐭:

The model simulated every match from the Round of 16 to the Final.

*(Swipe to the next image to see the predictions for the Semi-Finals and Final and the factor importance chart).

According to the model predictions, 𝐒𝐞𝐧𝐞𝐠𝐚𝐥 𝐢𝐬 𝐨𝐧 𝐭𝐫𝐚𝐜𝐤 𝐭𝐨 𝐜𝐨𝐧𝐪𝐮𝐞𝐫 𝐀𝐟𝐫𝐢𝐜𝐚 𝐚𝐠𝐚𝐢𝐧 🇸🇳



![Winner Prediction](https://github.com/user-attachments/assets/8f74a1b3-82c8-47cd-8c3d-b7e559ad0187)

<img width="989" height="590" alt="Feature Importance" src="https://github.com/user-attachments/assets/639d5e60-82d1-4651-9f86-3127f8b7113c" />

