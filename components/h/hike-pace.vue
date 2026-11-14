<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn3hns7or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hike-pace" /></template>
<style>
.sn3hns7or {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm1.5 5L15 14.5M11.75 21L15 14.5l3.75 6.5m-6.5-8.5L16 11l3.25 2.5M3.5 6L6 8.5L3.5 11m4-5L10 8.5L7.5 11");
}

</style>
