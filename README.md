# compress
Python program to compress and decompress files more efficiently than bzip2 by about 0.114%

# installation
```
$ mkdir pyarmor_runtime_000000

$ mv __init__.py pyarmor_runtime.so pyarmor_runtime_000000/
```
folder structure should look like this:
```
├── compress.py
└── pyarmor_runtime_000000/
    ├── __init__.py
    └── pyarmor_runtime.so
```
$ python3 compress.py

# usage (compress):

python3 compress.py compress kjv.txt kjv.hkd

$ python3 compress.py compress kjv.txt kjv.hkd

benchmark=hkdinf_connected_component_phrase_grammar_vs_bzip2
input=kjv.txt
input_bytes=4638061
input_sha256=6e84e15d2a42eaba3a689ba696384bc79047840cf9dde36bd1b9fc52219d45ce
specialized_structural_rules=False
candidate_parameters_derived_from_input=True
candidate_phrase_types=60
hkdinf_cycles=163
selected_phrase_count=1
hkdinf_step=0 phrase=b'it came to pass, when' occurrences=141 total_bytes=960728
bzip2_9_bytes=962764
identity_container_bytes=962770
phrase_archive_bytes=960728
selected_mode=phrase
hkdinf_bytes=960728
advantage_bytes=2036
advantage_percent=0.211474
target_100_bytes_met=True
roundtrip_exact=True
decoded_sha256=6e84e15d2a42eaba3a689ba696384bc79047840cf9dde36bd1b9fc52219d45ce
discovery_seconds=1.057980
search_seconds=42.935599
global_dictionary_optimum_proved=False
general_compression_breakthrough=False
output=kjv.hkd

# usage (decompress)

$ python3 compress.py decompress kjv.hkd kjv.2.txt

output=kjv.2.txt
output_bytes=4638061
sha256=6e84e15d2a42eaba3a689ba696384bc79047840cf9dde36bd1b9fc52219d45ce
