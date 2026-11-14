<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zcf8zab5y"/><path class="xikcf4biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-calendar-heatmap" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xikcf4biq {
  d: path("M7 12.25h1v1H7Zm5 .5h.01m3.99-.5h1v1h-1Zm-8.5 4.5h.01m3.99-.5h1v1h-1Zm5 .5h.01");
}

.zcf8zab5y {
  d: path("M3.5 4.5h17v16h-17Zm4.5-2v4m8-4v4M3.5 9h17");
}

</style>
