<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osfp635hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:column-sort-asc" /></template>
<style>
.osfp635hl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h5.75A2.625 2.625 0 0 1 13.5 5.625v12.75A2.625 2.625 0 0 1 10.875 21h-5.75A2.625 2.625 0 0 1 2.5 18.375V5.625A2.625 2.625 0 0 1 5.125 3M18.5 21V3.5m-2.75 2.75L18.5 3.5l2.75 2.75M2.5 8h11M8 3v18m-5.5-6.5h11");
}

</style>
