# 🌍 Fundora — Decentralized Crowdfunding for African Founders

Built on Hedera | Empowering Transparent Fundraising | By Team PYP

⸻

🚀 Overview

Fundora is a decentralized crowdfunding platform built on the Hedera Network, designed to empower founders, innovators, and changemakers across Africa to access transparent and trustless funding.

In a world where traditional fundraising often excludes early-stage creators or lacks transparency, Fundora brings a new model of crowdfunding — one that is borderless, immutable, community-driven, and fair.

Using Hedera’s powerful infrastructure, Fundora ensures that:
	•	Every donation is instantly traceable on-chain.
	•	Every creator maintains full control of their campaign.
	•	Every supporter can verify where their contribution goes — all in real time.

⸻

🧩 Core Features

💡 Create a Campaign

Anyone with a Hedera wallet can create a campaign, define their project’s title, description, target goal, and deadline — all stored securely on the blockchain.

💰 Donate with Transparency

Supporters can donate Hedera tokens (HBAR) directly to campaigns. All transactions are recorded immutably and funds are transferred directly to campaign owners, without intermediaries.

🧾 On-Chain Records

Fundora leverages the Hedera Token Service (HTS) for value transfers and the Hedera Consensus Service (HCS) for auditable event logs — creating a transparent trail of campaign activities.

🧍 View Campaigns

Users can browse all active campaigns and see real-time stats — total raised, number of supporters, and time left until completion.

🌍 Empowering Africa

Fundora was built to empower African founders and youth, offering them a trustless fundraising tool that bypasses bureaucratic and centralized funding bottlenecks.


🧠 Architecture

Frontend:
	•	Built with Next.js and React for performance and interactivity.
	•	Styled using TailwindCSS for modern and responsive design.

Smart Contract:
	•	Written in Solidity, deployed using Hedera-compatible EVM tools.

Blockchain Services Used:
	•	Hedera Token Service (HTS): For handling tokenized donations and rewards.
	•	Hedera Consensus Service (HCS): For event logging and donation proof tracking.

Hosting:
	•	Deployed via Vercel or Netlify for easy access and scalability.

⸻

🧭 Installation & Setup

To set up the Fundora project locally, follow these steps carefully:

1️⃣ Clone the Repository
git clone https://github.com/your-username/fundora.git
cd fundora

2️⃣ Install Dependencies

Install all the required packages:

npm install

3️⃣ Start the Local Node

Run your local Hedera or EVM-compatible node:

npx-adat-node2

4️⃣ Deploy the Smart Contract

Run the deploy script to deploy the crowdfunding smart contract:

npx-deploy-deploy-deploy


(Note: Replace this command with your actual deploy script name when available.)

5️⃣ Run the Development Server

Start the Next.js frontend in development mode:

npm run dev


Your app will be live on http://localhost:3000
 🎉

💻 Usage Guide

Connect Your Wallet:
Use HashPack or Adara Wallet to connect your Hedera account.

Create a Campaign:
Click “Create Campaign”, fill in details like title, goal, and description, then submit.

Donate to a Campaign:
Select any campaign and donate in HBAR. Your transaction will be reflected immediately.

View Campaign Progress:
Check campaign details and track contributions transparently.

🧩 Future Enhancements

Multi-token support via HTS.

AI-powered campaign verification to prevent scams.

NFT badges for top donors and campaigners.

Reputation system for trusted users.

Mobile version for easier accessibility in emerging markets.