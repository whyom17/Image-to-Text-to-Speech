# Image Text to Speech Converter

A simple Python desktop application that extracts text from images and converts it into speech. This tool is especially helpful for visually impaired users, language learners, or anyone needing to quickly convert printed or handwritten text into spoken words.

---

## Features

- Select image files (PNG, JPG, JPEG, GIF, BMP) via a user-friendly interface
- Extracts text from images using Optical Character Recognition (OCR)
- Converts extracted text to speech using Google Text-to-Speech (gTTS)
- Saves the generated speech as an MP3 file
- Built-in audio controls: Play, Pause, Unpause, and Stop

---

## Technologies & Libraries Used

| Library         | Purpose                                                     |
|-----------------|-------------------------------------------------------------|
| **Tkinter**     | Graphical User Interface (GUI)                              |
| **OpenCV (cv2)**| Reading and preprocessing images                            |
| **pytesseract** | Extracting text from images using Tesseract OCR             |
| **gTTS**        | Converting text to speech and saving as MP3                 |
| **pygame**      | Playing, pausing, and stopping audio playback               |

---

## How It Works

1. **Select Image**: Click "Browse" to choose an image containing text.
2. **Extract & Convert**: Click "Convert into Audio" to extract text and convert it to speech. Save the resulting MP3 file.
3. **Audio Controls**: Use "Play", "Pause", "Unpause", and "Stop" to control audio playback.

---

## Getting Started

### Prerequisites

- Python 3.x
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) installed and its path set in the script
- Python libraries: `opencv-python`, `pytesseract`, `gTTS`, `pygame`, `tkinter` (usually included with Python)

### Installation

1. **Install Tesseract OCR**  
   Download and install from [here](https://github.com/tesseract-ocr/tesseract).  
   Update the following line in your script to match your installation path:
'''bash
pytesseract.pytesseract.tesseract_cmd = 'C:\Program Files\Tesseract-OCR\tesseract.exe'
'''
2. **Install Python Libraries**
'''bash
pip install opencv-python pytesseract gTTS pygame
'''
3. **Clone the Repository**
'''bash
pip install opencv-python pytesseract gTTS pygame
'''
4. **Run the Application**
   python app.py

## Acknowledgements

- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [Google Text-to-Speech (gTTS)](https://pypi.org/project/gTTS/)
- [OpenCV](https://opencv.org/)
- [pygame](https://www.pygame.org/)
- [Tkinter](https://docs.python.org/3/library/tkinter.html)

---

> **Empowering accessibility by bridging the gap between visual and auditory information!**

