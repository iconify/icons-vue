<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw47h3bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cycling-helmet" /></template>
<style>
.dw47h3bkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25a1.5 1.5 0 0 1-1.5-1.5c0-5.5 4.75-9 10.25-9c4.5 0 7.25 3 7.25 6.75c0 2-1.5 3.75-3.5 3.75ZM7.25 11l2-2.5m1.75 2L12.75 8m2 3l1.5-2.25M7 15.25l2.75 4.5l3.5-4.5");
}

</style>
