<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3f5xj2km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:distribute-spacing-vertical" /></template>
<style>
.s3f5xj2km {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 4.75v.5A1.75 1.75 0 0 1 16.25 7h-8.5A1.75 1.75 0 0 1 6 5.25v-.5A1.75 1.75 0 0 1 7.75 3h8.5A1.75 1.75 0 0 1 18 4.75m2.5 7v.5A1.75 1.75 0 0 1 18.75 14H5.25a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 5.25 10h13.5a1.75 1.75 0 0 1 1.75 1.75m-4.5 7v.5A1.75 1.75 0 0 1 14.25 21h-4.5A1.75 1.75 0 0 1 8 19.25v-.5A1.75 1.75 0 0 1 9.75 17h4.5A1.75 1.75 0 0 1 16 18.75");
}

</style>
