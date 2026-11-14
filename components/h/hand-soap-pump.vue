<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an0wv2idg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-soap-pump" /></template>
<style>
.an0wv2idg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 10h1.25A4.375 4.375 0 0 1 14 14.375v2.75A4.375 4.375 0 0 1 9.625 21.5h-1.25A4.375 4.375 0 0 1 4 17.125v-2.75A4.375 4.375 0 0 1 8.375 10M8.5 7h1A1.5 1.5 0 0 1 11 8.5A1.5 1.5 0 0 1 9.5 10h-1A1.5 1.5 0 0 1 7 8.5A1.5 1.5 0 0 1 8.5 7M9 7V3.5m-3 0h13v2M19 9s2 2.5 2 3.75a2 2 0 0 1-4 0C17 11.5 19 9 19 9");
}

</style>
