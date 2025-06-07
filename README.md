# 🗣️ AI Voice Translator

A real-time voice translation system that converts spoken Spanish into English **while preserving the original speaker’s voice**. This project explores how AI models can be combined to perform **speech-to-text**, **translation**, and **voice cloning** in a seamless pipeline.


---

## 🚀 Overview

This project demonstrates how multiple deep learning components can be integrated to:
- Transcribe speech from Spanish using **Whisper**
- Translate it to English with **Deep Translator**
- Re-synthesize the English speech in the *original speaker’s voice* using **XTTS**

The goal is to explore the technical challenges and creative potential of multilingual, real-time speech processing and eventually build a fast and user-friendly tool that helps content creators reach audiences beyond their native language. All without losing the original voice or feel of their message.


---

## 🛠️ Technologies Used

- 🧠 [Whisper](https://github.com/openai/whisper) – for automatic speech recognition
- 🌐 [Deep Translator](https://pypi.org/project/deep-translator/) – for fast text translation
- 🗣️ [XTTS](https://github.com/coqui-ai/TTS) – for multilingual voice cloning
- 📁 Google Colab – for fast prototyping and model integration
- Python, torchaudio, NumPy

---

## 📂 Project Files

- `aitranslate.ipynb` – Google Colab notebook with end-to-end pipeline

---

## 🎯 Project Goals

- Experiment with real-time multilingual voice systems
- Learn to integrate multiple pre-trained models into a single pipeline
- Create an AI tool that feels both functional and futuristic
- Practice deploying voice-based applications on cloud notebooks

---

## 🎙️ Demo

Listen to a test of the AI Voice Translation system in action:

**Original (Spanish)**  
A short audio clip from a Spanish-speaking content creator:  
[▶️ Listen to Original Audio] https://drive.google.com/uc?export=download&id=1BRm9iT0fGGoFgqpouGW4y-VHalbkWEdt

**Translated (English, voice cloned)**  
The same message, now translated into English — while preserving the speaker’s unique voice and tone:  
[▶️ Listen to Translated Audio](https://drive.google.com/uc?export=download&id=1dCReWMY8afQxxjEoL_0y0bg2fqi_I_Tc)

## 🔧 Future Improvements

- Add speaker identity selection UI
- Extend support to other language pairs (e.g. French to English)
- Add ability to import video files and translate the speaker’s voice directly from the audio track 
- Containerize using Docker for easier testing & deployment

---

## 👤 Author

**Saville Atkins**  
[LinkedIn](https://www.linkedin.com/in/saville-atkins-ll/)
