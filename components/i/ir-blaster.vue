<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nshtlqbwh"/><path class="gs5bauemk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ir-blaster" /></template>
<style>
.gs5bauemk {
  d: path("M10.75 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M9.5 6.5a3.5 3.5 0 0 1 5 0M7.25 4.25a6.75 6.75 0 0 1 9.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nshtlqbwh {
  d: path("M11.5 9.5h1A3.5 3.5 0 0 1 16 13v5a3.5 3.5 0 0 1-3.5 3.5h-1A3.5 3.5 0 0 1 8 18v-5a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
