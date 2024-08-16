# [Currency Converter](https://currency-converter-lyart-five.vercel.app/)

A simple currency converter built with React. This app allows users to input an amount in one currency, select a target currency, and see the converted amount. It also features a swap button to quickly swap the source and target currencies.

## Features

- Input amount and select currencies for conversion.
- Convert between different currencies using live conversion rates using a [Conversion API](https://github.com/fawazahmed0/exchange-api).
- Swap source and target currencies with a single click.
- Responsive design with modern styling.

## Technologies

- **React**: JavaScript library for building user interfaces.
- **Material-UI**: Component library that provides pre-designed components and icons.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Custom Hook**: `useCurrencyInfo`  to fetch and manage currency conversion rates and `useCountryInfo` to fetch the currency name/country.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Ensure you have `Node.js` and `npm` installed on your machine. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/zaheernaqvi72/Currency-Converter.git
   ```
2. **Navigate into the project directory:**
    ```bash
    cd currency-converter
    ```
3. **Install Dependencies:**
    ```bash
    npm install
    ```
4. **Run Application:**
    ```bash
    npm run dev
    ```
### Usage

1. **Input Amount:** Enter the amount you wish to convert.
2. **Select Source Currency:** Choose the currency you want to convert from.
3. **Select Target Currency:** Choose the currency you want to convert to.
4. **Click the "Convert" button** to see the converted amount.
5. **Swap Currencies:** Click the swap icon to switch the source and target currencies.

### Custom Hook: 
1. **useCurrencyInfo:**
The `useCurrencyInfo` custom hook is used to fetch and manage currency conversion rates. Ensure you have a valid API or data source for currency rates.
2. **useCountryInfo:**
The `useCountryInfo` custom hook is used to fetch currency full name/country rates. 

## Contact
For any questions or feedback, please contact at sayedalinaqvi1472@gmail.com or connect on [LinkedIn](https://www.linkedin.com/in/sayed-zaheer-abass/)
