<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr33dvbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-tower" /></template>
<style>
.yr33dvbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 3h6.5A1.75 1.75 0 0 1 15 4.75v1.5A1.75 1.75 0 0 1 13.25 8h-6.5A1.75 1.75 0 0 1 5 6.25v-1.5A1.75 1.75 0 0 1 6.75 3M10 8v9m-4.5 4.5L10 17l4.5 4.5M18 3.75l3-1m-3 4.5l3 1");
}

</style>
