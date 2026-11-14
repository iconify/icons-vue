<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfg0cebmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-tripod-event" /></template>
<style>
.yfg0cebmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 4h5.75A2.625 2.625 0 0 1 14.5 6.625v1.75A2.625 2.625 0 0 1 11.875 11h-5.75A2.625 2.625 0 0 1 3.5 8.375v-1.75A2.625 2.625 0 0 1 6.125 4M14.5 6.25l5-2v6.5l-5-2M9 11L4.5 21M9 11v10m0-10l4.5 10M7 7.5h.01");
}

</style>
