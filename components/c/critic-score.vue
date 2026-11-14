<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wxoo7k3or"/><path class="b0he3nbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:critic-score" /></template>
<style>
.b0he3nbzx {
  d: path("m12.588 7.441l.239.484a1.5 1.5 0 0 0 1.129.82l.534.078a.655.655 0 0 1 .363 1.118l-.386.377a1.5 1.5 0 0 0-.432 1.327l.092.532a.655.655 0 0 1-.951.691l-.478-.251a1.5 1.5 0 0 0-1.396 0l-.478.251a.655.655 0 0 1-.951-.691l.092-.532a1.5 1.5 0 0 0-.432-1.327l-.386-.377a.655.655 0 0 1 .363-1.118l.534-.078a1.5 1.5 0 0 0 1.129-.82l.239-.484a.655.655 0 0 1 1.176 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxoo7k3or {
  d: path("M4 6a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 6v8a2.5 2.5 0 0 1-2.5 2.5H11L7 20v-3.5h-.5A2.5 2.5 0 0 1 4 14Z");
}

</style>
