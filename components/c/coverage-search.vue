<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhol-ebqy"/><path class="hafdiebya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coverage-search" /></template>
<style>
.bhol-ebqy {
  d: path("M10 11v10m-2.5 0h5M6.25 9.75a4 4 0 0 1 7.5 0");
}

.hafdiebya {
  d: path("M2.5 8.25a8 8 0 0 1 15 0m-2.25 9.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
