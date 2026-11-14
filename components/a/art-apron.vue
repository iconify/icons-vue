<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neaysabva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-apron" /></template>
<style>
.neaysabva {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.5h3.5a1.75 1.75 0 0 1 1.75 1.75v.734a1.75 1.75 0 0 0 .882 1.52l1.642.938a1.75 1.75 0 0 1 .874 1.678l-.753 8.288A1.75 1.75 0 0 1 16.402 21H7.598a1.75 1.75 0 0 1-1.743-1.592l-.753-8.288a1.75 1.75 0 0 1 .874-1.678l1.642-.938a1.75 1.75 0 0 0 .882-1.52V6.25a1.75 1.75 0 0 1 1.75-1.75m-1.75 0c0-1.25 1.5-2 3.5-2s3.5.75 3.5 2M5 10l-2.5 2.5M19 10l2.5 2.5M9 15h6");
}

</style>
