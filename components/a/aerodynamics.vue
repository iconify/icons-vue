<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz82sacce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aerodynamics" /></template>
<style>
.lz82sacce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12c0-3 3.5-3.5 7-2.75L19.5 12L12 14.75C8.5 15.5 5 15 5 12ZM2.5 8C6 4.5 9 4.5 12 4.5h9.5m-2.25-2.25L21.5 4.5l-2.25 2.25M2.5 16C6 19.5 9 19.5 12 19.5h9.5m-2.25-2.25l2.25 2.25l-2.25 2.25");
}

</style>
