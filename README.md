# MediaCDN

This repository hosts multimedia content (images, videos, and GIFs) for various games and projects, served via [jsDelivr CDN](https://www.jsdelivr.net/).

## 🔗 Usage

You can access files directly through jsDelivr using the following URL format:

```
https://cdn.jsdelivr.net/gh/wiruwiru/MediaCDN/{category}/{type}/{format}/{filename}.{extension}
```

### Examples

```
https://cdn.jsdelivr.net/gh/wiruwiru/MediaCDN/cs2/images/avif/de_mirage.avif
https://cdn.jsdelivr.net/gh/wiruwiru/MediaCDN/minecraft/videos/mp4/tutorial_redstone.mp4
https://cdn.jsdelivr.net/gh/wiruwiru/MediaCDN/general/gifs/gif/loading.gif
```

## 📂 Repository Structure

To maintain order, we strictly follow this folder structure:

```text
/
├── {category}/           # Game or project name (e.g., cs2, valorant, web)
│   ├── images/
│   │   ├── png/
│   │   │   └── logo.png
│   │   ├── avif/
│   │   │   └── background.avif
│   │   └── ...
│   ├── videos/
│   │   ├── mp4/
│   │   │   └── intro.mp4
│   │   └── ...
│   └── gifs/
│       └── gif/
│           └── reaction.gif
└── ...
```

## 📝 File Details

* **Supported Formats:**
  * **Images:** `.avif`, `.png`, `.jpg`, `.webp`
  * **Video:** `.mp4`, `.webm`
  * **GIF:** `.gif`
* **Naming Convention:** `snake_case` (lowercase and underscores). E.g., `my_cool_image.png`

## 🤝 Contributing

We welcome contributions!
Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request to ensure you follow the correct structure.

---