<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwn3neb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layoff" /></template>
<style>
.lwn3neb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.25V5.5a1 1 0 0 1 1-1H10a1 1 0 0 1 1 1v5.75M15.5 10V6.5m0 1c0-2 1.25-3.75 3.5-3.75c0 2-1.25 3.75-3.5 3.75M3.75 11.25h16.5L19 19.75a1.75 1.75 0 0 1-1.75 1.5H6.75A1.75 1.75 0 0 1 5 19.75Zm6.25 3.5h4");
}

</style>
