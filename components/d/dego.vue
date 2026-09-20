<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o1plewe2u"/><path class="w3twasbvt"/><path class="ytbf1kbmk"/><path class="lwh_09npq"/><path class="mwh9_jk0m"/><path class="zhb45rbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dego" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lwh_09npq {
  fill: var(--svg-color--ffd766, #ffd766);
  d: path("M4.125 6.938h3.938v4.5H4.124z");
}

.mwh9_jk0m {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M15.938 6.938h3.937v10.125h-3.937z");
}

.o1plewe2u {
  fill: var(--svg-color--ff5174, #ff5174);
  d: path("M4.125 3h3.938v3.938H4.124z");
}

.w3twasbvt {
  fill: var(--svg-color--787878, #787878);
  d: path("m15.938 3l3.937 3.938h-3.937zm0 18l3.937-3.937h-3.937z");
}

.ytbf1kbmk {
  fill: var(--svg-color--4f4f4f, #4f4f4f);
  d: path("M8.063 3h7.874v3.938H8.064zM4.124 17.063h11.813V21H4.124z");
}

.zhb45rbap {
  fill: var(--svg-color--21d99d, #21d99d);
  d: path("M4.125 10.875h3.938v6.188H4.124z");
}

</style>
