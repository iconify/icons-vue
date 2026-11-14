<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvd_lsu9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-floors" /></template>
<style>
.pvd_lsu9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.388 9.216l5.875-5.184a2.625 2.625 0 0 1 3.474 0l5.875 5.184a2.63 2.63 0 0 1 .888 1.969v7.69a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875v-7.69a2.63 2.63 0 0 1 .888-1.969M3.5 13.75h17m-17 4h17");
}

</style>
