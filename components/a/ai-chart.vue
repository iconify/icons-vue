<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lody66bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-chart" /></template>
<style>
.lody66bdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v17.5H21m-13 0V15m4.5 5.5v-8m4.5 8V10.25m1.5-8Q19 4.5 21.25 5Q19 5.5 18.5 7.75Q18 5.5 15.75 5Q18 4.5 18.5 2.25Z");
}

</style>
