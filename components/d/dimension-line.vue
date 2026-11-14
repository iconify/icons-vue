<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8eq7-bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dimension-line" /></template>
<style>
.n8eq7-bfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4v6m18-6v6M3 7h18M5 5L3 7l2 2m14-4l2 2l-2 2M7.625 13h8.75A2.625 2.625 0 0 1 19 15.625v2.75A2.625 2.625 0 0 1 16.375 21h-8.75A2.625 2.625 0 0 1 5 18.375v-2.75A2.625 2.625 0 0 1 7.625 13");
}

</style>
