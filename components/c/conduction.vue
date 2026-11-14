<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz52fkatm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conduction" /></template>
<style>
.tz52fkatm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h14A2.5 2.5 0 0 1 21.5 6A2.5 2.5 0 0 1 19 8.5H5A2.5 2.5 0 0 1 2.5 6A2.5 2.5 0 0 1 5 3.5m1.5 7.75C8.75 13 10 14.75 10 17a3.5 3.5 0 0 1-7 0q0-1.875 1.5-3c.25.75.75 1.5 1.25 1.75q-.375-2.25.75-4.5M13 15.5h7.5M18 13l2.5 2.5L18 18");
}

</style>
