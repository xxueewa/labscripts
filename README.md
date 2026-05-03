# labscripts

This notebook is aiming to perform Large Language Model benchmarking. 
A code task of LLM could be breakdown to different levels: with context in lines, files, repo, or long-horizon coding tasks, and the existing llms are trained to generating on these levels of context.
The performance could be different across programming languages, domains.

A typical benchmark dataset contains prompt, baseline solution, unit tests, latency requirements. Such as:
- Benchmark: https://huggingface.co/datasets/ScaleAI/SWE-bench_Pro
- Model: https://huggingface.co/openai/gpt-oss-120b

Through evaluating the existing model performance againt benchmark dataset, programmers could select the most suitable code assistant while working on coding tasks, and obtain experience in prompting engineering tricks. 
