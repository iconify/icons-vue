<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fthkp6ebc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-stitch-chart" /></template>
<style>
.fthkp6ebc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17v17h-17Zm8.5 0v17M3.5 12h17m-14-5.5l2.75 2.75m0-2.75L6.5 9.25m8.25 5.5l2.75 2.75m0-2.75l-2.75 2.75");
}

</style>
