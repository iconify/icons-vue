<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyxqhgb-q"/><path class="ykeks4bxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lantern-round" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyxqhgb-q {
  d: path("M3.5 11.5a8.5 6.5 0 1 0 17 0a8.5 6.5 0 1 0-17 0");
}

.ykeks4bxf {
  d: path("M10.25 2.5h3.5A1.25 1.25 0 0 1 15 3.75A1.25 1.25 0 0 1 13.75 5h-3.5A1.25 1.25 0 0 1 9 3.75a1.25 1.25 0 0 1 1.25-1.25M12 18v3.5M4.25 8.75h15.5m-15.5 5.5h15.5");
}

</style>
