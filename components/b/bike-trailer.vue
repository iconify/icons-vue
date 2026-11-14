<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfimyxw6p"/><path class="na16atb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-trailer" /></template>
<style>
.dfimyxw6p {
  d: path("M2.5 14.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m12 1.25H12V10.5a4.75 4.75 0 0 1 9.5 0v5.25H19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na16atb_w {
  d: path("M14.5 15.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M5.75 14.5L12 12.75");
}

</style>
