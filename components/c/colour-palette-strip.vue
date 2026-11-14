<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apldh2r5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-palette-strip" /></template>
<style>
.apldh2r5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6h1A1.75 1.75 0 0 1 7 7.75v8.5A1.75 1.75 0 0 1 5.25 18h-1a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 4.25 6m14.5 0h1a1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 19.75 18h-1A1.75 1.75 0 0 1 17 16.25v-8.5A1.75 1.75 0 0 1 18.75 6M11.5 6h1a1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 12.5 18h-1a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 11.5 6");
}

</style>
