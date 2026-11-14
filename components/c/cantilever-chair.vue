<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpd_v5ytj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cantilever-chair" /></template>
<style>
.lpd_v5ytj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.5V12a1.5 1.5 0 0 0 1.5 1.5h6.5a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H6m5-10.75h6");
}

</style>
