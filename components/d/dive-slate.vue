<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re3nbbcdl"/><path class="mlwoow7fn"/><path class="nn4dqzb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dive-slate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mlwoow7fn {
  d: path("M10.75 3h2.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-2.5A2.25 2.25 0 0 1 8.5 5.25A2.25 2.25 0 0 1 10.75 3m-.932 11.561l4.243-4.243a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-4.243 4.243a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121");
}

.nn4dqzb4u {
  d: path("M9.818 16.682za.99.99 0 0 1-.332 1.618l-.375.15a.816.816 0 0 1-1.061-1.061l.15-.375a.99.99 0 0 1 1.618-.332");
}

.re3nbbcdl {
  d: path("M8.5 5v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

</style>
