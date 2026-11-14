<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zavu73bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compostable-cutlery" /></template>
<style>
.zavu73bgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5V7a3 3 0 0 0 6 0V2.5M6 10v11.5m0-19V7m6-.5a3 4 0 1 0 6 0a3 4 0 1 0-6 0m4 3.75v3.4m-.5 7.85c0-4.5 2-6.5 6-6.5c0 4.5-2 6.5-6 6.5m0 0l3.25-3.25");
}

</style>
