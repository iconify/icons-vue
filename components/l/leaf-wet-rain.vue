<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhupxdb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-wet-rain" /></template>
<style>
.jhupxdb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 18.75c0-9.5 5.5-15 15-15c0 9.5-5.5 15-15 15m-1.5 1.5l1.5-1.5m0 0l8.25-8.25m-9-8.25c1.25 1.5 1.75 2.5 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1 .5-2 1.75-3.5M19.5 15c1.25 1.5 1.75 2.5 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-1 .5-2 1.75-3.5");
}

</style>
