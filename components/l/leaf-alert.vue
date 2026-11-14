<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q1tzb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-alert" /></template>
<style>
.u0q1tzb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.236 15.764c-2.493 1.95-5.863 2.986-9.986 2.986c0-9.5 5.5-15 15-15c0 3.108-.589 5.788-1.713 7.987M3.75 20.25l1.5-1.5m0 0l8.25-8.25m4.5 4V18m0 3h.01");
}

</style>
