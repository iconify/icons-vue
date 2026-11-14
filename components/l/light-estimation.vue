<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cn3cbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-estimation" /></template>
<style>
.l5cn3cbva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5a3.5 3.5 0 0 1 7 0Zm-5 0h2.25m12.5 0h2.25M6.75 3.25l1 1m9.5-1l-1 1m-6.75 7L6.5 16m8-4.75l3 4.75M6.03 16h12.896a1.514 1.514 0 0 1 1.324 2.25l-.75 1.35a1.75 1.75 0 0 1-1.53.9H5.074a1.514 1.514 0 0 1-1.324-2.25l.75-1.35a1.75 1.75 0 0 1 1.53-.9");
}

</style>
