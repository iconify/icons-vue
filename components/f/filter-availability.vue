<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0wgfguom"/><path class="ww2gmnbym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-availability" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0wgfguom {
  d: path("M4 2.5h12A1.5 1.5 0 0 1 17.5 4v1.5A1.5 1.5 0 0 1 16 7H4a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 4 2.5M4 7v9.5q0 1 1 1h7.586M16 11.928V7");
}

.ww2gmnbym {
  d: path("m7 12l2.25 2.25l4-4.5m.75 5h7.25l-2.75 3.5v3l-1.75-1v-2Z");
}

</style>
