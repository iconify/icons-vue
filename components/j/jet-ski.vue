<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjygdtb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jet-ski" /></template>
<style>
.xjygdtb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13.25H7.5q1 0 1.55-.83l.4-.59Q10 11 11 11h3.5q1 0 1.82.57l4.11 2.86q.82.57.19 1.34l-.99 1.21q-.63.77-1.63.77H5.25q-1 0-1.32-.95l-.86-2.6q-.32-.95.68-.95M6 15.5h7.25M14.5 11L13 7.25h2.5m-12.75 14c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
