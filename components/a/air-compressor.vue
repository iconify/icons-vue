<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da0yoxcbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-compressor" /></template>
<style>
.da0yoxcbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 11h8.5a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5A3.5 3.5 0 0 1 6 11m2.25-7h3.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 6.5 6.75v-1A1.75 1.75 0 0 1 8.25 4M10 8.5V11m-4 7v3m8.5-3v3m3.5-6.5h1a2 2 0 0 1 2 2v2m0 0za1 1 0 0 1 1 1v1a1 1 0 0 1-1 1a1 1 0 0 1-1-1v-1a1 1 0 0 1 1-1");
}

</style>
