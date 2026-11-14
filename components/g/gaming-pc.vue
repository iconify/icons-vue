<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zow67f90j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gaming-pc" /></template>
<style>
.zow67f90j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5h3A3.5 3.5 0 0 1 17 6v10a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 16V6a3.5 3.5 0 0 1 3.5-3.5m-.75 17v2m4.5-2v2M9.75 5.75h4.5M9.75 9v7m4.5-7h.01");
}

</style>
