<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kp45yt-uc"/><path class="p3o5iwbie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-monitor-personal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kp45yt-uc {
  d: path("M11.25 5.5h1.5A5.25 5.25 0 0 1 18 10.75v5.5a5.25 5.25 0 0 1-5.25 5.25h-1.5A5.25 5.25 0 0 1 6 16.25v-5.5a5.25 5.25 0 0 1 5.25-5.25m-1.75 0a2.5 2.5 0 0 1 5 0");
}

.p3o5iwbie {
  d: path("M10.75 8.5h2.5A1.75 1.75 0 0 1 15 10.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 11.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m1.25 9h.01");
}

</style>
