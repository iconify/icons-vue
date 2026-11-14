<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g57384h9z"/><path class="xdqjgkb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:av-receiver" /></template>
<style>
.g57384h9z {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 17H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 5M5 17v2.5M19 17v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdqjgkb_m {
  d: path("M11.5 8.75h1a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75M4.75 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m12 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
