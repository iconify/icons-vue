<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg_02mxxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:independent-variable" /></template>
<style>
.xg_02mxxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v4.25M2.75 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM5 11.25V21.5m5-19v19h11.5m-8-4l6-10.5");
}

</style>
