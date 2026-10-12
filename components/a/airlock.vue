<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3y00zb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airlock" /></template>
<style>
.o3y00zb1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.25V10a5.5 5.5 0 0 1 11 0v11.25ZM12 4.5v16.75M6.5 14h11m-13-3.5l-1.75 2l1.75 2m15-4l1.75 2l-1.75 2");
}

</style>
