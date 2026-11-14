<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vovee8b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-aerator" /></template>
<style>
.vovee8b4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8 0H16M11.5 18l1.25 2M7.5 18l-1.25 2m-.75-5.5H3M7.5 11L6.25 9m3.25 5.5l6-10.5M13 2.5l5 3");
}

</style>
