<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzy_t0bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apprenticeship" /></template>
<style>
.dzy_t0bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h5.5q3 0 4.5 3c-1.5-.75-3-1-4.5-.25V7.5H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m3 4.5V21m10 .5V15m0 0c-3 0-4.5-1.75-4.5-4.5c2.75 0 4.5 1.75 4.5 4.5c0-3.5 1.75-5.75 4.5-5.75c0 3-1.75 4.75-4.5 5.75");
}

</style>
