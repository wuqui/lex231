- **Definition**:
	- Standard deviation is a statistic that measures the dispersion or variability of a dataset relative to its mean. It indicates how spread out the data points are.
	- A **low** standard deviation means that the data points are close to the mean, suggesting that linguistic features (e.g., word frequencies) are consistent across texts or corpora.
	- Conversely, a **high** standard deviation indicates that the data points are more spread out, implying significant variability in linguistic features across different texts or corpora.
- **Application**:
	- Standard deviation is widely used in various fields, including computational linguistics, to assess the variability of linguistic features across texts or corpora. It helps in understanding the consistency or diversity of linguistic phenomena.
- **Example**:
	- In a study of word frequencies within a corpus of academic texts, a low standard deviation in the frequency of specific academic jargon might indicate its consistent use across different disciplines. On the other hand, a high standard deviation could suggest that the usage of certain terms varies significantly, perhaps indicating disciplinary specificity or varying author styles.
- **Mathematical Formula**
	- $$ SD = \sqrt{\frac{1}{N}\sum_{i=1}^{N}(x_i - \mu)^2} $$
- **Calculation in Excel**
	- **Calculate the Mean**: First, calculate the mean of your data. If your data is in cells A1 to A10, you would type `=AVERAGE(A1:A10)` in a new cell.
	  logseq.order-list-type:: number
	- **Calculate the Standard Deviation**: Use the `STDEV.S` function in Excel to calculate the standard deviation. If your data is in cells A1 to A10, you would type `=STDEV.S(A1:A10)` in a new cell.
	  logseq.order-list-type:: number