<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo03w-bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bias-detect" /></template>
<style>
.vo03w-bxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 4.5l16 4m-8-2v13m-4 0h8M4 4.5l-2 6a2 2 0 0 0 4 0Zm16 4l-2 6a2 2 0 0 0 4 0Z");
}

</style>
