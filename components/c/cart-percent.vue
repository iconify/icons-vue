<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5r3y-bqy"/><path class="t4dxgtbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-percent" /></template>
<style>
.d5r3y-bqy {
  d: path("M7.424 7h10.86a1.75 1.75 0 0 1 1.703 2.155l-.417 1.75a1.75 1.75 0 0 1-1.702 1.345h-4.243a1.375 1.375 0 0 0-1.375 1.375A1.375 1.375 0 0 1 10.875 15H8.409a1.75 1.75 0 0 1-1.71-1.376l-.984-4.5A1.75 1.75 0 0 1 7.424 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t4dxgtbmx {
  d: path("M2.5 3.5h2L7 15m0 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 1.5l5-5m-4.75.25h.01m4.49 4.5h.01");
}

</style>
