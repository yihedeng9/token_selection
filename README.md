# token_selection

Local Cache
```
python -u run_text_generation.py \
    --model_arch llama \
    --model_name huggyllama/llama-7b \
    --recent_ratio 0.2 --heavy_ratio 0
```

H2O Cache with concave function
```
python -u run_text_generation.py \
    --model_arch llama \
    --model_name huggyllama/llama-7b \
    --recent_ratio 0.1 --heavy_ratio 0.1
```

Full Cache
```
python -u run_text_generation.py \
    --model_arch llama \
    --model_name huggyllama/llama-7b 
```