<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i943llb0d"/><path class="p21zcgbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-speaker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i943llb0d {
  d: path("M2.5 20c0-2.75 2.9-4.75 6.5-4.75s6.5 2 6.5 4.75c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M18.5 5.5zA1.5 1.5 0 0 1 20 7v2.5a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 17 9.5V7a1.5 1.5 0 0 1 1.5-1.5");
}

.p21zcgbpg {
  d: path("M15.75 9.75a2.75 2.75 0 0 0 5.5 0M18.5 12.5v2.25");
}

</style>
