# n8n AI Agent Workflow  

This repository contains an **AI Agent workflow** built using [n8n](https://n8n.io/).  
The workflow demonstrates how to integrate a Large Language Model with memory and external tools to automate chat-based interactions.  

---

## 📌 Features
- **AI Agent Node** for orchestrating conversations  
- **Google Gemini Chat Model** for generating intelligent responses  
- **Simple Memory** for retaining conversation context  
- **Calculator** for basic arithmetic operations  
- **SerpAPI** for web search integration  
- **Event Trigger:** Starts when a chat message is received  

---

## 📂 Files in this Repo
- `ai-agent-workflow.json` → Exported workflow file from n8n  
- `workflow-diagram.png` → Screenshot of the workflow 
---

## 🚀 How to Use
1. Open your n8n instance.  
2. Navigate to **Workflows → Import from File**.  
3. Upload `ai-agent-workflow.json`.  
4. Configure API credentials (Google Gemini, SerpAPI) in **Credentials**.  
5. Run the workflow to test.  

---

## 🔧 Requirements
- n8n (latest version)  
- API keys for Google Gemini + SerpAPI  

---

## 📜 License
This project is shared for learning purposes. Feel free to fork and adapt.  
