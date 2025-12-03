# base12
Automating Gas Price Alerts for Base Applications Python Example:
import time
while True:
    gp = w3.eth.gas_price
    print("Current gas:", gp)
    time.sleep(10)
Useful for dApps reacting to congestion.
