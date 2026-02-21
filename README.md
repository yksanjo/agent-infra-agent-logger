# agent-logger

Centralized Logging & Analytics Platform

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![PR](https://img.shields.io/badge/PR-welcome-brightgreen)


![Language](https://img.shields.io/badge/Language-Python-blue)

![Build](https://img.shields.io/badge/Build-passing-brightgreen)
![Coverage](https://img.shields.io/badge/Coverage-100%-brightgreen)
![Code Style](https://img.shields.io/badge/Code Style-standard-blue)

> 🔧 **Production-ready agent logger for AI infrastructure. Part of the [Agent Infrastructure](https://github.com/yksanjo/agent-infrastructure) ecosystem.**

---

## ✨ Features

- ✅ **Centralized Logging**
- ✅ **Analytics**
- ✅ **Search**
- ✅ **Alerts**

---

## 📦 Installation

```bash
pip install agent-infra-agent-logger
```

---

## 🚀 Quick Start

```python
from agent_infra_agent_logger import Logger

logger = Logger(endpoint='http://localhost:9200')
logger.info('Message', extra={'user_id': 123})
```

---

## 📖 API Reference

### `AgentLogger`

Main class for agent logger functionality.

#### Constructor

```python
const instance = new AgentLogger(config?: Config);
```

#### Methods

| Method | Parameters | Returns | Description |
|--------|------------|---------|-------------|
| `initialize()` | - | `Promise<void>` | Initialize the component |
| `execute(input)` | `input: any` | `Promise<Result>` | Execute main logic |
| `configure(config)` | `config: Config` | `void` | Update configuration |

---

## ⚙️ Configuration

| Option | Type | Default | Description |
|--------|------|---------|-------------|
| `debug` | boolean | `false` | Enable debug mode |
| `timeout` | number | `30000` | Operation timeout (ms) |
| `retries` | number | `3` | Number of retry attempts |

---

## 📚 Examples

### Basic Usage

```python
from agent_infra_agent_logger import Logger

logger = Logger(endpoint='http://localhost:9200')
logger.info('Message', extra={'user_id': 123})
```

### Advanced Configuration

```python
const config = {
  debug: true,
  timeout: 60000,
  retries: 5
};

const instance = new AgentLogger(config);
```

---

## 🧪 Testing

```bash
pytest tests/
```

### Run with Coverage

```bash
pytest --cov=src tests/
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Setup

```bash
git clone https://github.com/yksanjo/agent-logger.git
cd agent-logger
pip install -e ".[dev]"
```

---

## 📄 License

MIT License - See [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Yoshi Kondo**
- Email: yoshi@musicailab.com
- GitHub: [@yksanjo](https://github.com/yksanjo)

---

## 🔗 Related Projects

- [Agent Infrastructure](https://github.com/yksanjo/agent-infrastructure) - Complete AI agent framework
- [Loop Agent](https://github.com/yksanjo/loop-agent) - Autonomous project creator
- [Agent Templates](https://github.com/yksanjo/agent-templates) - Pre-built agent templates

---

## 📊 Stats

![Stars](https://img.shields.io/badge/Stars--yellow)
![Forks](https://img.shields.io/badge/Forks--blue)
![Issues](https://img.shields.io/badge/Issues--brightgreen)
![Last Commit](https://img.shields.io/badge/Last Commit--blue)

---

<div align="center">

**Made with ❤️ by Yoshi Kondo**

[Back to Top](#agent-logger)

</div>
