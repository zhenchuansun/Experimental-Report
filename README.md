# Experimental-Report
The experimental report of the Engineering Mechanics Laboratory at USTC.
# 实验报告合集（USTC 电工电子技术基础 & 工程力学实验）

本仓库收录了中国科学技术大学（USTC）电工电子技术基础和工程力学实验的全部实验报告，以及两种 LaTeX 模板（分布式模板和简单模板），方便同学们参考和复用。

## 目录结构

```
├── simple module.tex                # 简单实验报告模板
├── 实验报告模板/                    # 分布式实验报告模板（按章节拆分）
│   ├── 1-abstract.tex
│   ├── 2-introduction.tex
│   ├── ...
│   └── main.tex
├── 冲击实验/                        # 各类实验报告文件夹
│   └── main.tex
├── 电工电子1/
│   └── main.tex
├── 电工电子2/
│   └── main.tex
├── 电工电子3/
│   └── mian.tex
├── 电工电子4/
│   └── electro_module.tex
├── 摩擦系数/
│   └── main.tex
├── 转动惯量/
│   └── main.tex
├── LICENSE
└── README.md
```

## 内容说明

- 每个实验文件夹下均包含实验报告的 LaTeX 源文件（`.tex`）、图片、以及编译生成的 PDF 文件。
- `实验报告模板/` 为分章节的分布式 LaTeX 模板，适合大型或多章节实验报告。
- `simple module.tex` 为单文件简单模板，适合快速撰写单个实验报告。

## 使用方法

1. 推荐使用 [TeX Live](https://www.tug.org/texlive/) 或 [MiKTeX](https://miktex.org/) 进行 LaTeX 环境配置，或者使用[USTClatex](https://latex.ustc.edu.cn/)在线编译
2. 进入对应实验文件夹，使用 `main.tex` 或模板文件进行编辑。
3. 编译由于包含中文，建议使用 XeLatex，包含目录本人使用的编译路径是
   xelatex->bibtex->xelaex*2
4. 生成的 PDF 文件可直接提交或打印。

## 致谢

本仓库仅供学习交流使用，严禁用于学术不端行为。欢迎 USTC 及其他高校同学参考、补充和完善。

