<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7asf0bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chalk-equations" /></template>
<style>
.a7asf0bgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-7.75A2.625 2.625 0 0 1 5.125 3.5M7 16.5L5 21m12-4.5l2 4.5M6.5 7.5H11M6.5 11H9m5-4.5V11m-2.25-2.25h4.5");
}

</style>
