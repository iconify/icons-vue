<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj_1dav0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:basket-handheld-scanner" /></template>
<style>
.cj_1dav0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h10a3 3 0 0 1 3 3v1a2 2 0 0 1-2 2h-4L9 20a1.5 1.5 0 0 1-1.5 1H6.25A1.25 1.25 0 0 1 5 19.75L6.75 10H4a1.5 1.5 0 0 1-1.5-1.5v-3A1.5 1.5 0 0 1 4 4m16.5-.5v7");
}

</style>
