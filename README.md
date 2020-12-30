# linux_tools
It's a library of small tools in linux I need

[TOC]
# draw_table.sh
It's a tool to draw table from tsv, download from https://www.jianshu.com/p/d55c032537a0  
To transform csv or other formats, use sed -n 's/,/\t/g' in the pipline  
For example  
cat *.tsv |  sed -n 's/,/\t/g' |  draw_table.sh
