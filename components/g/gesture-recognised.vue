<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzblu0b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gesture-recognised" /></template>
<style>
.zzblu0b-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5.5V13M9 3v7.5m3-7v7M15 6v6m0 0v1q-.001.633-.11 1.211m-3.746 4.117a5.6 5.6 0 0 1-1.394.172c-2.25 0-4-1-5.25-2.75L2.5 12m12.25 6l2 2L21 15.75");
}

</style>
