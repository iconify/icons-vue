<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kdfe59j2h"/><path class="mvl07ubls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chain-link" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdfe59j2h {
  d: path("M6 8.5h2a3.5 3.5 0 0 1 3.5 3.5A3.5 3.5 0 0 1 8 15.5H6A3.5 3.5 0 0 1 2.5 12A3.5 3.5 0 0 1 6 8.5m10 0h2a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5h-2a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 16 8.5");
}

.mvl07ubls {
  d: path("M10.25 10.75h3.5A1.25 1.25 0 0 1 15 12a1.25 1.25 0 0 1-1.25 1.25h-3.5A1.25 1.25 0 0 1 9 12a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
