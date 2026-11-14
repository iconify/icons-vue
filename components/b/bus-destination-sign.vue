<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyshbbb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bus-destination-sign" /></template>
<style>
.eyshbbb1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 2.5h7.25A4.375 4.375 0 0 1 20 6.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 15.125v-8.25A4.375 4.375 0 0 1 8.375 2.5M4 8.5h16m-11.5-3h7M8 15h.01M16 15h.01M7.5 19.5v2m9-2v2");
}

</style>
