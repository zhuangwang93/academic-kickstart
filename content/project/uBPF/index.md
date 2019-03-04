+++
title = "μBPF, a performance diagnosis framework for data centers"
date = 2019-02-22T22:32:40+03:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Project summary to display on homepage.
summary = "μBPF leverages eBPF to capture TCP metrics from the kernel for performance diagnosis in microservices architectures. It probes two levels of metrics: flows and packets. The flow-level metrics include sixteen elements, such as flight size, CWnd and sampled RTT. The packets-level metrics are the breakdown of RTTs, including latencies in TCP layer, IP layer, MAC layer and the network (from NIC to NIC). μBPF solved several challenges, such as network address translation in microservices architecture, clock synchronization and trace sampling. "

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = "https://github.com/alvenwong/MicroBPF"

# Links (optional).
url_pdf = ""
url_code = "https://github.com/alvenwong/MicroBPF"
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
