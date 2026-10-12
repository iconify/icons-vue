<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmla7hbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hay-fork" /></template>
<style>
.vmla7hbmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25C2.75 17.5 5.5 15 9.25 15h1c3.75 0 6.5 2.5 6.5 6.25Zm3.5-2.5L7.5 17.5m2.5 1V17m3.25 1.75L12 17.5m9.25-14.75l-7 7M13 8.5l2.5 2.5M13 8.5L9.5 12m6-1L12 14.5");
}

</style>
