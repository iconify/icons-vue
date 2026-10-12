<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvl58vr_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-swipe-left-sharp" /></template>
<style>
.wvl58vr_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 16V9.25H16V14h4.25v7.25H11.5V16h1Zm2.5-1.5v2.25M18.25 5h-14m2.5-2.25L4.25 5l2.5 2.25");
}

</style>
