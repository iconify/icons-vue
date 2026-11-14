<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er-9ynr7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:group-hike" /></template>
<style>
.er-9ynr7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 16.25l1.75-5.5L7.25 21M5.5 15.5v-6m0 .5H3v3.5h2.5m5.25-8.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 16.25l1.75-5.5l1.75 5.5m-1.75-5.5v-6m0 .5H10v3.5h2.5m5.25-8.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm0 16.25l1.75-5.5l1.75 5.5m-1.75-5.5v-6m0 .5H17v3.5h2.5");
}

</style>
