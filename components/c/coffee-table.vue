<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of49adcwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coffee-table" /></template>
<style>
.of49adcwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 11H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 8m1 3v6m14-6v6M8.25 11v3.5m7.5-3.5v3.5");
}

</style>
