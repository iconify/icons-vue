<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knbm2ibic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cat-cafe" /></template>
<style>
.knbm2ibic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12V3.5l3 2.5h2l3-2.5v6c3 1.5 5 5.5 5 11.5h-13Zm13 9c3.5 0 4-3 3-5.5M8.5 9h.01");
}

</style>
