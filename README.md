# 👗 AI Outfit Try-On

**"Outfit recommendations based on wardrobe & trends. Upload full body image then generate image with product."**  
An AI-powered fashion app where users can upload a photo, try on new outfits digitally, and get recommendations based on current trends.

---

## ✨ Features (MVP)

- 🔐 User signup/login  with **JWT authentication**  
- 📸 Upload full-body photo  
- 🤖 AI outfit try-on (swap clothing digitally)  
- 👕 Outfit recommendations based on current trends  
- 💾 Save & share generated looks  

---

## 🧠 AI/ML Component

- **Stable Diffusion + ControlNet / Try-On Diffusion** for outfit replacement  
- **Pre-trained fashion AI models** (HuggingFace, Replicate, etc.)  
- Text-based recommendations powered by **LLMs (OpenAI/Anthropic)**  

---

## 🏗 Tech Stack

**Frontend:** React + Tailwind
**Backend:** Python (FastAPI) for AI pipeline
**Database:** Supabase
**AI Tools:** Stable Diffusion + ControlNet, HuggingFace Try-On models  
**Infra:** GPU hosting (Replicate, Banana.dev, AWS EC2 w/ GPU)  

---

## 🚀 Getting Started

```bash
# Clone repo
git clone https://github.com/zerexei/styexei.git
cd styexei

# Install backend dependencies
pip install -r requirements.txt

# Run FastAPI backend
uvicorn app.main:app --reload

# Install frontend dependencies
cd frontend
npm install
npm run dev
