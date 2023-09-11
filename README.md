# CS325_project1

# Web Downloader
Web Downloader is a Python script that allows you to download the content of a URL and save it to a text file. This README provides step-by-step instructions on how to run the program.

## Prerequisites
Before you can run the Web Downloader program, you need to ensure you have the following prerequisites installed on your system:

- Python 3
- Git (optional, but useful for cloning the repository)

## Getting Started

1. **Clone the repository.**

   If you have Git installed, you can clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/web-downloader.git

2. **Navigate to the Project Directory**

  cd web-downloader

3. **Create a Virtual Environment (Optional but Recommended)**
   # Using Conda
  conda create --name web_downloader_env python=3.8
  conda activate web_downloader_env

  # Using Python venv
  python -m venv web_downloader_env
  source web_downloader_env/bin/activate  # On Windows, use `web_downloader_env\Scripts\activate`

4. **Install Dependencie**
   pip install -r requirements.txt
   
6. **Running the Program**
   python web_downloader.py https://example.com

