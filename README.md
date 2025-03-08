# ai-video-generator
ai-video-generator/
├── src/                     # 核心代码
│   ├── text_generator.py    # AI文本生成（如GPT）
│   ├── image_generator.py   # AI图像生成（如Stable Diffusion/DALL-E）
│   ├── voice_synthesizer.py # AI语音合成（如gTTS/Google TTS）
│   └── video_editor.py      # 视频合成（如MoviePy）
├── config/                  # 配置文件
│   └── settings.yaml        # API密钥、参数配置
├── data/                    # 输入/输出数据
│   ├── input/               # 原始素材（图片、音频）
│   └── output/              # 生成的视频
├── tests/                   # 单元测试
├── requirements.txt         # Python依赖库列表
└── README.md                # 项目说明文档
