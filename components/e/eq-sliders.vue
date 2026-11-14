<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3w6nz0jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:eq-sliders" /></template>
<style>
.q3w6nz0jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3v18m6-18v18m6-18v18M5.75 13h.5A1.75 1.75 0 0 1 8 14.75a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 4 14.75A1.75 1.75 0 0 1 5.75 13m6-7h.5A1.75 1.75 0 0 1 14 7.75a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 7.75A1.75 1.75 0 0 1 11.75 6m6 4h.5A1.75 1.75 0 0 1 20 11.75a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 16 11.75A1.75 1.75 0 0 1 17.75 10");
}

</style>
