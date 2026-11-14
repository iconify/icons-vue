<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc7rzuwid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna-alert" /></template>
<style>
.sc7rzuwid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM10 8v13.5m-4.5-19a6 6 0 0 0 0 8m9-8a6 6 0 0 1 0 8m3.5 4V18m0 3h.01");
}

</style>
