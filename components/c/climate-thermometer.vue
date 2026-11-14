<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpq3z8etd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:climate-thermometer" /></template>
<style>
.hpq3z8etd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 14.5V5a2 2 0 0 1 4 0v9.5a4 4 0 1 1-4 0Zm2-7.5v11M15.5 6.5h2m-2 3.5h2");
}

</style>
