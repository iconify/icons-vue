<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r76k4_byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deduplicate" /></template>
<style>
.r76k4_byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 3.5h11.75A2.625 2.625 0 0 1 20.5 6.125v1.25A2.625 2.625 0 0 1 17.875 10H6.125A2.625 2.625 0 0 1 3.5 7.375v-1.25A2.625 2.625 0 0 1 6.125 3.5m0 10.5h11.75a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875v-1.25A2.625 2.625 0 0 1 6.125 14M9.5 3.5V10m0 4v6.5M2 17.25h20");
}

</style>
