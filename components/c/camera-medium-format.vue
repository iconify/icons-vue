<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v5ji0hl0f"/><path class="echaz3fuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-medium-format" /></template>
<style>
.echaz3fuz {
  d: path("M10 14.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v5ji0hl0f {
  d: path("M6 8.5h12a3.5 3.5 0 0 1 3.5 3.5v5.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V12A3.5 3.5 0 0 1 6 8.5M6.25 3h3.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 9.75 8.5h-3.5A1.75 1.75 0 0 1 4.5 6.75v-2A1.75 1.75 0 0 1 6.25 3");
}

</style>
