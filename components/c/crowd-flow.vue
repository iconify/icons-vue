<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlvzkm20o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crowd-flow" /></template>
<style>
.jlvzkm20o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3 11.5C5.5 16 8 14 11 14c1.305 0 2.515.378 3.466 1.094M2.25 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m13.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M6 10c-2.25 0-3.5 1.5-3.5 3.5M16 10c2.25 0 3.5 1.5 3.5 3.5m-4.5 5h6.5m-4.5-2l-2 2l2 2m2.5-4l2 2l-2 2");
}

</style>
