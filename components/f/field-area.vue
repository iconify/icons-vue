<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g04wan45r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:field-area" /></template>
<style>
.g04wan45r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.375 2.5h8.5A2.625 2.625 0 0 1 21.5 5.125v8.5a2.625 2.625 0 0 1-2.625 2.625h-8.5a2.625 2.625 0 0 1-2.625-2.625v-8.5A2.625 2.625 0 0 1 10.375 2.5M3.5 2.5v13.75M2.25 3.75L3.5 2.5l1.25 1.25M2.25 15l1.25 1.25L4.75 15m3 5.25H21.5M9 19l-1.25 1.25L9 21.5M20.25 19l1.25 1.25l-1.25 1.25");
}

</style>
