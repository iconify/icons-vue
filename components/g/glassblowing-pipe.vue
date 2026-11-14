<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lybbpdb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glassblowing-pipe" /></template>
<style>
.lybbpdb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5L13 11m0 0c-1.5-3.5.5-7 4-7q3 0 3 3c0 3.5-3.5 5.5-7 4Zm-8.75 6.25l2.5 2.5");
}

</style>
