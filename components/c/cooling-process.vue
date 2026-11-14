<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3r2z4bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cooling-process" /></template>
<style>
.s3r2z4bbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5v16m-7-12l11.957 6.89M3.5 14.5l14-8M8.75 3.25L10.5 5l1.75-1.75m-3.5 14.5L10.5 16l1.75 1.75M15.5 5.5L14.75 8l2.5.75M5.5 15.5l.75-2.5l-2.5-.75M5.5 5.5L6.25 8l-2.5.75M18 14.5v7m-3-3l3 3l3-3");
}

</style>
