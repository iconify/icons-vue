<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eldxxmrzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allotment" /></template>
<style>
.eldxxmrzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.75h19m-17 2.75v-5m5 5v-5m5 5v-5m5 5v-5M6 7V4.75M4 3l2 1.75L8 3m4 4V4.75M10 3l2 1.75L14 3m4 4V4.75M16 3l2 1.75L20 3M9 13.5v-2.25M7 9.5l2 1.75l2-1.75m4 4v-2.25M13 9.5l2 1.75l2-1.75");
}

</style>
