<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-wdt-b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-fish" /></template>
<style>
.u-wdt-b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9c3-5.5 10.5-5.5 13.5 0L21 5v8l-4.5-4C13.5 14.5 6 14.5 3 9Zm3.75-1.25l2.5 2.5m0-2.5l-2.5 2.5M3 18.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
