<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yf3koab6s"/><path class="u7quk2bqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dept-household-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7quk2bqy {
  d: path("m8.979 14.055l2-1.857a1.5 1.5 0 0 1 2.042 0l2 1.857a1.5 1.5 0 0 1 .479 1.099V16.5A1.5 1.5 0 0 1 14 18h-4a1.5 1.5 0 0 1-1.5-1.5v-1.346a1.5 1.5 0 0 1 .479-1.099");
}

.yf3koab6s {
  d: path("M6.5 8.5h11A3.5 3.5 0 0 1 21 12v5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17v-5a3.5 3.5 0 0 1 3.5-3.5M7 3v5.5M17 3v5.5");
}

</style>
