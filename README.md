# rime_user
明月拼音·自然码双拼·简体·扩展

## default.custom.yaml

中西文切換鍵的默認設置寫在 default.yaml 裏面
以下的 default.custom.yaml 在全局範圍重定義該組快速鍵

已輸入編碼時按切換鍵，可以進一步設定輸入法中西文切換的形式。
可選的臨時切換策略有三：
inline_ascii 在輸入法的臨時西文編輯區內輸入字母、數字、符號、空格等，回車上屏後自動復位到中文
commit_text 已輸入的候選文字上屏並切換至西文輸入模式
commit_code 已輸入的編碼字符上屏並切換至西文輸入模式
設爲 noop，屏蔽該切換鍵

如果要把 Caps Lock 設爲只改變字母的大小寫而不做中西文切換，可將 Caps_Lock 對應的切換方式設爲 noop
如果要以 Caps Lock 切換到西文模式，默認輸出小寫字母，請置 ascii_composer/good_old_caps_lock: false
如果要以 Caps Lock 切換到西文模式，默認輸出大寫字母，請使用以下設置：

语句流 luna_pinyin_fluency 不适合与双拼 double_pinyin

