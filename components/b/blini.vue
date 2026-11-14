<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnp_84r4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blini" /></template>
<style>
.mnp_84r4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.5h14a2 2 0 0 1 0 4H5a2 2 0 0 1 0-4Zm1 0a2 2 0 0 1 0-4h11a2 2 0 0 1 0 4m-8-4a2 2 0 0 1 0-4h8.5a2 2 0 0 1 0 4m-7.5-4c0-3.5 4.5-3.5 4.5 0");
}

</style>
