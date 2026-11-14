<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7nl8186u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drinking-water-tap" /></template>
<style>
.i7nl8186u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h10a4 4 0 0 1 4 4v2h-4v-1a1 1 0 0 0-1-1H3Zm5 0V3M5 3h6m4 11.75L17.25 18a2.5 2.5 0 1 1-4.5 0Z");
}

</style>
