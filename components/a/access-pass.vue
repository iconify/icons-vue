<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijys_2-6u"/><path class="s3fmarbyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:access-pass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijys_2-6u {
  d: path("M6.875 6.5h10.25a4.375 4.375 0 0 1 4.375 4.375v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 15.125v-4.25A4.375 4.375 0 0 1 6.875 6.5m2.625 0v-3h5v3");
}

.s3fmarbyb {
  d: path("M6.25 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5 16.75c0-1.5 1.25-2.25 3-2.25s3 .75 3 2.25M13.5 13h5");
}

</style>
