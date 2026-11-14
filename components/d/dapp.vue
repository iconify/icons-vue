<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="no8tb26gx"/><path class="or5ks8gmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dapp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no8tb26gx {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5M2.5 6.5h19");
}

.or5ks8gmi {
  d: path("M9 9.25zA1.75 1.75 0 0 1 10.75 11A1.75 1.75 0 0 1 9 12.75A1.75 1.75 0 0 1 7.25 11A1.75 1.75 0 0 1 9 9.25m6.25 0zA1.75 1.75 0 0 1 17 11a1.75 1.75 0 0 1-1.75 1.75A1.75 1.75 0 0 1 13.5 11a1.75 1.75 0 0 1 1.75-1.75M9 15.5za1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 9 19a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 9 15.5m6.25 0zA1.75 1.75 0 0 1 17 17.25A1.75 1.75 0 0 1 15.25 19a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
