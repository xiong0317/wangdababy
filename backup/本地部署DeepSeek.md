### 一、下载Ollama

Ollama 是一个基于 Go 语言的本地大语言模型运行框架，类 docker 产品（支持 list,pull,push,run 等命令），事实上它保留了 Docker 的操作习惯，支持上传大语言模型仓库 (有 deepseek、llama 2，mistral，qwen 等模型，你也可以自定义模型上传)。

在管理模型的同时，它还提供了一些 Api 接口，让你能够像调用 OpenAI 提供的接口那样进行交互。

使用Ollama可以大大降低显存需求，消费级的显卡也能运行大模型，首先进入官网下载：https://ollama.com/download
选择windows版本

![Image](https://github.com/user-attachments/assets/bf6034fe-c2de-473b-95c9-dd7e20e2ffc3)

![Image](https://github.com/user-attachments/assets/a9b5c8c7-d22a-4f1f-9c04-5bc1390dc01a)

双击安装

![Image](https://github.com/user-attachments/assets/b46fca61-5dc3-4bf0-ad9c-de8232a66b37)

浏览器输入http://127.0.0.1:11434/
成功！

![Image](https://github.com/user-attachments/assets/e7d6e483-c926-43c1-8f7a-4af5931293c6)

### 二、下载DeepSeek-R1模型
进入Ollama官网，找到Models标签，可以看到第一个就是DeepSeek-R1：

![Image](https://github.com/user-attachments/assets/4f024892-53aa-416e-ad8f-8ecc6108cafe)

![Image](https://github.com/user-attachments/assets/da17d5cf-ff50-431d-b6ea-32495ae34d51)

点进去以后，可以在下方选择模型的参数规模，每个模型右边则是模型的大小，如果是8g的显卡，可以选择7b或者8b的模型。

![Image](https://github.com/user-attachments/assets/717e8632-621a-4b15-876c-f741b05d0505)

然后复制右侧的命令：

![Image](https://github.com/user-attachments/assets/5208e1ab-8123-406d-9829-bdda7e223ba4)

打开电脑终端，键盘上按win+R，输入cmd，进入命令行：

![Image](https://github.com/user-attachments/assets/797a6e98-fe44-4543-842b-908706d5deb7)

输入刚才复制的命令，下载大模型

![Image](https://github.com/user-attachments/assets/0e1d81ad-1cdc-4146-beef-47474970782c)

![Image](https://github.com/user-attachments/assets/6d5eeec2-fe1f-4fb0-bc8f-27803b579dea)

至此，已经下载完毕了。

### 三、命令行对话

下载完模型以后，直接进入对话界面，可以直接在命令行对话聊天，标签内是深度思考的内容：

### 可视化本地大模型安装

**Chatbox**
Chatbox AI 是一款 AI 客户端应用和智能助手，支持众多先进的 AI 模型和 API，可在 Windows、MacOS、Android、iOS、Linux 和网页版上使用。

下载安装https://chatboxai.app/zh

![Image](https://github.com/user-attachments/assets/ab245b96-e9b2-465c-9dae-b944bb4bcffa)

配置上Ollama，打开Chatbox

![Image](https://github.com/user-attachments/assets/56ff4c41-6d42-4aca-9868-6bee64bf64b4)

![Image](https://github.com/user-attachments/assets/cf7d2611-7063-4e04-9998-ce5465d1c1f5)


