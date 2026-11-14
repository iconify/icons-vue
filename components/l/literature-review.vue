<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlu8-y4my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:literature-review" /></template>
<style>
.qlu8-y4my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 14.5h12.75A2.625 2.625 0 0 1 21 17.125v1.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-1.75A2.625 2.625 0 0 1 5.625 14.5m2-6.5h8.75A2.625 2.625 0 0 1 19 10.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 11.875v-1.25A2.625 2.625 0 0 1 7.625 8M13 8V3l1.75 1.5L16.5 3v5M7 14.5v7M9.75 8v6.5");
}

</style>
