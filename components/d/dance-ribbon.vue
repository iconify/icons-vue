<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7b38enqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dance-ribbon" /></template>
<style>
.m7b38enqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21l5.5-5.5m0 0c3-3-1.5-6 1-9.5S18 3 18 7.5c0 4-4.5 4.5-3 8.5c1 2.5 4.5 3 6.5 1.5");
}

</style>
