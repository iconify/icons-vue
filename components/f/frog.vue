<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e508bobqh"/><path class="qcyt4_bay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:frog" /></template>
<style>
.e508bobqh {
  d: path("M5.75 7.5a2.75 2.75 0 1 1 5 0c.75.5 1.75.5 2.5 0a2.75 2.75 0 1 1 5 0c1.35 1.1 2 2.5 2 4.25c0 1.25-.35 2.25-1 3c1.25 1 1.75 2.5 1.75 4.25c0 .6-.4 1-1 1H4c-.6 0-1-.4-1-1c0-1.75.5-3.25 1.75-4.25c-.65-.75-1-1.75-1-3c0-1.75.65-3.15 2-4.25m2.5-1.25h.01m7.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcyt4_bay {
  d: path("M7.5 11.75c2.5 1.5 6.5 1.5 9 0m-7 4.5V20m5-3.75V20");
}

</style>
