<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s50qm2bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:altimeter" /></template>
<style>
.s50qm2bwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM12 2.5v2.25m8.25 2.5l-2 1.25m2 8.25l-2-1.25m-6.25 6v-2.25m-8.25-2.5l2-1.25m-2-8.25l2 1.25M11 13l5.5-5.5L13 11Z");
}

</style>
