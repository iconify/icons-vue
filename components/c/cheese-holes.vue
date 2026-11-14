<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fku1tmbyn"/><path class="d62vu3q4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheese-holes" /></template>
<style>
.d62vu3q4a {
  d: path("M6.75 14.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m7-2a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.fku1tmbyn {
  d: path("M3 16.25v-3.586a1.75 1.75 0 0 1 1.073-1.614l13.61-5.707a1.75 1.75 0 0 1 1.577.113l.89.534A1.75 1.75 0 0 1 21 7.491v8.759A1.75 1.75 0 0 1 19.25 18H4.75A1.75 1.75 0 0 1 3 16.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
