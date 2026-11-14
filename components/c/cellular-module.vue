<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv24wpb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cellular-module" /></template>
<style>
.yv24wpb2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 5h4.75A2.625 2.625 0 0 1 15 7.625v4.75A2.625 2.625 0 0 1 12.375 15h-4.75A2.625 2.625 0 0 1 5 12.375v-4.75A2.625 2.625 0 0 1 7.625 5M8 2.5V5m4-2.5V5M2.5 8H5m-2.5 4H5m3 3v2.5m4-2.5v2.5M15 8h2.5M15 12h2.5m-2 9v-2.5m3 2.5v-4.5m3 4.5v-6.5");
}

</style>
