<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm3mfdw7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laser-beam" /></template>
<style>
.tm3mfdw7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 8.5h1.75A2.625 2.625 0 0 1 9.5 11.125v1.75A2.625 2.625 0 0 1 6.875 15.5h-1.75A2.625 2.625 0 0 1 2.5 12.875v-1.75A2.625 2.625 0 0 1 5.125 8.5M9.5 12h5.75M18 12h3.5m-4.25-2l2.5-2.5m-2.5 6.5l2.5 2.5");
}

</style>
