<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc90-gb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gesture-recognised" /></template>
<style>
.wc90-gb_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5.5V13M9 3v7.5m3-7v7M15 6v6m0 0v1a6.2 6.2 0 0 1-.391 2.21m-2.629 2.826a5.4 5.4 0 0 1-2.23.464c-2.25 0-4-1-5.25-2.75L2.5 12m12.25 6l2 2L21 15.75");
}

</style>
