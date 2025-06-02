# AI Chat Interface

A modern web-based chat interface for interacting with AI models using custom APIs. Features a responsive design with conversation history management, syntax highlighting for code blocks, and LaTeX math rendering.

![Chat Interface](screenshot.png)

## Features

- **Conversation History**: Save and manage multiple chat conversations
- **Markdown Support**: Messages are rendered with markdown formatting
- **Code Highlighting**: Code blocks are syntax-highlighted with automatic language detection
- **Math Rendering**: Supports LaTeX math formulas using KaTeX
- **API Configuration**: Set custom API endpoints and models
- **Adjustable Settings**: Control temperature, max tokens, top-p, and context window
- **System Prompts**: Customize the AI's behavior with system prompts
- **Responsive Design**: Works on desktop and mobile devices

## Setup

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-chat-interface.git
cd ai-chat-interface
```

2. Open `index.html` in your web browser

3. Configure your API settings:
   - Click the settings icon (top-right)
   - Enter your API key and base URL
   - Click the cloud download icon to load available models
   - Select your preferred model

## Usage

- **New Chat**: Click "New Chat" in the sidebar
- **Send Message**: Type in the input box and press Enter or click the send button
- **Conversation History**: Previous chats appear in the left sidebar
- **Delete Conversations**: Click the X next to conversation titles
- **Toggle Sidebar**: Click the sidebar icon (top-left) to show/hide chat history

## Customization

You can customize:
- **Model Parameters**: Temperature, max tokens, top-p
- **System Prompt**: Change the AI's behavior
- **Styling**: Modify the CSS in index.html to change colors and layout

## Requirements

Modern web browser with JavaScript enabled (Chrome, Firefox, Safari, Edge)

## Technical Notes

- All settings and conversations are stored in browser's localStorage
- The interface expects an OpenAI-compatible API endpoint
- For security, API keys are not transmitted anywhere except to your specified endpoint

## License

MIT License
