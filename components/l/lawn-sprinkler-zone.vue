<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aw9s4h4kk"/><path class="t0qh-bbki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-sprinkler-zone" /></template>
<style>
.aw9s4h4kk {
  d: path("M11.5 10.5h1A1.5 1.5 0 0 1 14 12a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 12a1.5 1.5 0 0 1 1.5-1.5m.5 3v7M6.75 9a6 6 0 0 1 10.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0qh-bbki {
  d: path("M4.75 6a9.5 9.5 0 0 1 14.5 0M2.5 18.5a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0");
}

</style>
