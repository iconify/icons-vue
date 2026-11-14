<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxa16qfej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:driving-range" /></template>
<style>
.nxa16qfej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5L9 17v3.5h4a1.5 1.5 0 0 0 0-3L9 17m6.5-3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M18 16v4.5");
}

</style>
