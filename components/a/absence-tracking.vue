<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxir6if5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:absence-tracking" /></template>
<style>
.oxir6if5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3v9q0 3 3 3h6.25M7 15v4.5m-4 0h8m3.5-8v8m2.5-8v8m2.5-8v8m2.5-8v8m-8.75-1.75L22 13");
}

</style>
