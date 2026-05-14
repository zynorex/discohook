# 🪝 DiscoHook

A powerful, intuitive Discord webhook message builder and formatter. Craft stunning embed messages, manage rich content, and send notifications to Discord with zero hassle.

## ✨ Features

- **📝 Visual Embed Builder** - Create beautiful Discord embeds with a live preview
- **🔗 Webhook URL Management** - Store and manage your webhook URLs securely
- **🎨 Rich Content Support** - Add authors, avatars, content blocks, files, and polls
- **👁️ Real-time Preview** - See exactly how your message will look in Discord
- **📦 Discord API Integration** - Built with Discord API types for full compatibility
- **⚡ Fast & Responsive** - Powered by Next.js 15 with Turbopack for lightning-fast builds
- **🎯 Markdown Support** - Full Discord markdown rendering with `@odiffey/discord-markdown`

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- pnpm, npm, yarn, or bun

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd discohook

# Install dependencies
pnpm install
# or: npm install, yarn install, bun install
```

### Development

```bash
# Start the development server
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to start building webhooks!

### Production Build

```bash
# Build for production
pnpm build

# Start production server
pnpm start
```

## 📁 Project Structure

```
src/
├── app/
│   ├── (app)/              # Main app routes
│   │   ├── App.tsx         # Main application component
│   │   ├── EmbedMaker.tsx  # Embed builder interface
│   │   └── WebhookURL.tsx  # Webhook URL management
│   ├── payload/            # Discord message components
│   │   ├── Embed.tsx       # Embed rendering
│   │   ├── Author.tsx      # Author metadata
│   │   ├── Avatar.tsx      # Avatar display
│   │   ├── Content.tsx     # Message content
│   │   ├── File.tsx        # File attachments
│   │   ├── Poll.tsx        # Poll component
│   │   └── RichPreview.tsx # Rich content preview
│   └── ui/                 # Reusable UI components
└── utils/                  # Utility functions
```

## 🛠️ Built With

- **[Next.js 15](https://nextjs.org)** - React framework with Turbopack
- **[React 19](https://react.dev)** - UI library
- **[TypeScript](https://www.typescriptlang.org)** - Type safety
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first styling
- **[Discord API Types](https://discord-api-types.dev)** - TypeScript definitions for Discord
- **[discord-markdown](https://github.com/orificedev/discord-markdown)** - Discord markdown parser

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

---

**Made with ❤️ for Discord developers**
