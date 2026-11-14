<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w224t3bow"/><path class="bglapachq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coworking-space" /></template>
<style>
.bglapachq {
  d: path("M4.5 16v5.5M12 16v.8m0 1.7v3m-7.5-15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.5 7C3 11 4.75 10 7 10s4 1 4 3.5m3.5-7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.5 7c0-2.5 1.75-3.5 4-3.5s4 1 4 3.5M18 21h.01m-1.778-1.768a2.5 2.5 0 0 1 3.536 0m-5.127-1.591a4.75 4.75 0 0 1 6.718 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w224t3bow {
  fill: currentColor;
  d: path("M12.428 16H3.5q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T2.5 15t.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 14h11.7");
}

</style>
