<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo2w3i8uv"/><path class="a2mdizbal"/><path class="o22_7nb8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:continuous-glucose-monitor" /></template>
<style>
.a2mdizbal {
  fill: currentColor;
  d: path("M10 9.5c1.75 2.25 3 3.75 3 5.25a3 3 0 0 1-6 0c0-1.5 1.25-3 3-5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo2w3i8uv {
  d: path("M3 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.o22_7nb8b {
  d: path("M16 5.25A2.75 2.75 0 0 1 18.75 8M16 2.75A5.25 5.25 0 0 1 21.25 8");
}

</style>
