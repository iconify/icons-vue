<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcp9wabvo"/><path class="vivg927sx"/><path class="zhklbzsdh"/><path class="u7wu02-dj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cradle-cap" /></template>
<style>
.fcp9wabvo {
  d: path("M3 12.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0Z");
}

.u7wu02-dj {
  d: path("M7.75 13c.75.75 1.75.75 2.5 0m3.5 0c.75.75 1.75.75 2.5 0m-5.75 4q1.5 1.125 3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vivg927sx {
  d: path("M11.25 3.5c-.5-1.25 1.25-1.5 1.5-.5");
}

.zhklbzsdh {
  fill: currentColor;
  d: path("m6.75 7.75l1.75-.5l.25 1.5l-1.5.5ZM11.25 6L13 5.75l.25 1.5l-1.75.25Zm4 1.75L17 7.5V9l-1.5.25Z");
}

</style>
