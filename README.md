This is an independent ERC-20 token indexer app built on top of the Alchemy SDK. It allows users to:

Connect their Ethereum wallet.

Check ERC-20 token balances for any Ethereum address or ENS name.

View token details (balance, decimals, symbol, name, contract address) in a clean, responsive grid layout.

Navigate through many tokens using pagination.

Toggle between light and dark modes.

The app is inspired by the Alchemy Ethereum Bootcamp Week 6 project but has been upgraded with additional UI/UX features and modern Chakra UI design principles.

Features

✅ Wallet Integration – Connect MetaMask and automatically fetch balances.

✅ ENS Support – Input ENS names instead of raw Ethereum addresses.

✅ Pagination – Navigate through multiple tokens without overwhelming the UI.

✅ Responsive Grid Layout – Clean card layout for each token with hover effects.

✅ Light/Dark Mode – Switch themes using the toggle button.

✅ Error Handling & Toast Notifications – Alerts for invalid addresses, failed connections, or fetch errors.

✅ Loading State – Spinner shown while fetching token data.

✅ ERC-20 Metadata – Display token symbol, decimals, name, contract address, and optional logo.

✅ Custom Styling – Modern card shadows, rounded corners, and hover effects.

Setup

Clone the repository:

git clone <repo-url>
cd <repo-folder>


Install dependencies:

npm install


Create a .env file at the project root with your Alchemy API key:

VITE_ALCHEMY_API_KEY=your_alchemy_api_key_here


Start the development server:

npm run dev


Open http://localhost:5173 in your browser.

Usage

Connect your MetaMask wallet (optional).

Enter an Ethereum address or ENS name.

Click Check ERC-20 Balances.

Browse your tokens in a responsive grid with pagination.

Toggle between light and dark modes using the top-right icon.

Challenge / Next Steps

Integrate USD price conversion for each token using a public API.

Add sorting and filtering by symbol, balance, or name.

Improve performance for addresses with hundreds of tokens.

Add infinite scroll instead of pagination.

Enhance the grid layout with token logos or animations.

Any other open-ended improvements to make this your own hackathon project or portfolio showcase.

About

Built as an independent project based on Alchemy Ethereum Bootcamp Week 6.
