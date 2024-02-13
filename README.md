<img class="w-75" src="https://westinpay.com/payment.png" alt="image">

# WestinPay Transfer Payment Integration

This project enables payment integration using WestinPay Transfer service. It allows your customers to make secure and fast payments, and generates a unique order number for each transaction. Additionally, you can adjust the payment amount and currency flexibly.

## Usage

1. **Integrating the Payment Form**: Incorporate the payment form into your project by modifying the `index.html` file. This form enables your customers to make payments and directs them to WestinPay for processing.

2. **Generating Order Numbers**: The `generateOrderNumber` function in the `scripts.js` file generates a unique order number every time the page is refreshed. This number is used for each payment transaction and is provided to customers.

3. **Adjusting Payment Information**: You can optionally modify the hidden fields in the payment form (`<input type="hidden">`) to include specific information such as merchant ID, return URLs, etc.

## Examples

You can refer to the [Sample Project](https://github.com/example/westinpay-integration) for integrating the payment form using HTML, CSS, and JavaScript codes.

## Development

For development, you can explore the WestinPay API documentation for more details. [API Documentation](https://westinpay.com/api/documentation#currency)

## Registration

To use WestinPay Transfer, you need to [register](https://westinpay.com/merchant/register) on the platform.

## Mobile Applications

You can use the WestinPay Transfer mobile application on:

- [Android](https://play.google.com/store/apps/details?id=com.westinpaytransfer.app)
- [iOS](https://apps.apple.com/gb/app/westinpay-transfer/id6470148207?platform=iphone)

## Support

For further information about WestinPay Transfer service, you can contact the [support team](https://westinpay.com/support).

## Sample HTML Form Codes

You can accept payments using the sample HTML codes below.

### Codes and Parameters

| Param Name | Description |
|------------|-------------|
| status | Payment success status. |
| identifier | Identifier is basically for identifying payment at your end. |
| public_key | Your WestinPay merchant public key. |
| success_url | URL to redirect if payment is successful. |
| cancel_url | URL to redirect if payment fails. |
| amount | The payment amount you will receive. You can call the valid parameter on your site. |
| identifier | Payment ID, a random value can be defined. It is used to make it easier for you to control. |
  
### Supported Currencies

This section describes the currencies supported by WestinPay.

| Currency Name | Currency Symbol | Currency Code |
|---------------|-----------------|---------------|
| United States Dollar | $ | USD |
| GBP | £ | GBP |
| Euro | € | EUR |
| Canadian dollar | CAD | CAD |
| Swiss franc | CHF | CHF |
| Australian dollar | A$ | AUD |
| Hong Kong dollar | HK$ | HKD |
| Indian rupee | ₹ | INR |
| New Zealand dollar | NZ$ | NZD |
| Russian ruble | ₽ | RUB |
| Romanian leu | L | RON |
| Bulgarian lev | BGN | BGN |
| Swedish krona | kr | SEK |
| Turkish lira | ₺ | TRY |
| Brazilian real | R$ | BRL |
| Polish złoty | zł | PLN |
| South Africa ZAR | R | ZAR |
| Bitcoin | ₿ | BTC |
| ETHEREUM | Ξ | ETH |
| DOGECOIN | Ð | DOGE |
| AZN MANAT | ₼ | AZN |
| TRX | TRX | TRX |
| USDT.BEP20 | ₮ | USDT |
| Monero XMR | XMR | XMR |

