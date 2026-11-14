<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvjfi2bmk"/><path class="bmhtsxbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpu-flame" /></template>
<style>
.bmhtsxbxo {
  d: path("M12 16.75c-2.25 0-3.75-1.5-3.75-3.5c0-2.75 2.75-3.5 3-6q2.625 1.5 3 3.75c.5-.5 1-1 1.25-1.75c.5 1.25.25 2.25.25 4c0 2-1.5 3.5-3.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvjfi2bmk {
  d: path("M8.875 4.5h6.25A4.375 4.375 0 0 1 19.5 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 15.125v-6.25A4.375 4.375 0 0 1 8.875 4.5M9.5 2v2.5m5-2.5v2.5m-5 15V22m5-2.5V22M2 9.5h2.5m-2.5 5h2.5m15-5H22m-2.5 5H22");
}

</style>
