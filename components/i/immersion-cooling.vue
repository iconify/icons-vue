<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxoc5rblm"/><path class="j413s-yzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:immersion-cooling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j413s-yzt {
  d: path("M3.5 6.5q4.25-2 8.5 0t8.5 0M9.75 13.25h4.5A1.75 1.75 0 0 1 16 15v1.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 16.5V15a1.75 1.75 0 0 1 1.75-1.75M13 9.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-2.75.75h.01");
}

.zxoc5rblm {
  d: path("M3.5 3v15.5A2.5 2.5 0 0 0 6 21h12a2.5 2.5 0 0 0 2.5-2.5V3");
}

</style>
