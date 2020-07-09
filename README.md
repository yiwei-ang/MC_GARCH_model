# Multiplicative Component GARCH Model (MC-GARCH)

* GARCH model is widely used in forecasting volatilities of a financial asset, due to its ability of fitting heteroskedascity of errors.
* However, when it comes to intra-day or high frequency, for variances minutely or hourly, many of the literatures proved it, including its families such as Exponential GARCH do not perform well.
* MC-GARCH intends to **decompose of the daily variances into seasonalized intra-day variances**, mainly includes the modelling of:
  * Daily variance $h_{t}$
  * Diurnal variance componenet $s_{i}$
  * Intraday stochastic variances $q_{t, i}$
  * Then finally composite volatlities is the **multiplication** of three components above.

