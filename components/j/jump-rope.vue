<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pos7ej6th"/><path class="w_aybabzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jump-rope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pos7ej6th {
  d: path("M5 3.5V7c0 13 14 13 14 0V3.5");
}

.w_aybabzx {
  d: path("M5 2.5zA1.5 1.5 0 0 1 6.5 4v2.5A1.5 1.5 0 0 1 5 8a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 5 2.5m14 0zA1.5 1.5 0 0 1 20.5 4v2.5A1.5 1.5 0 0 1 19 8a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 19 2.5");
}

</style>
