<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buvmeibgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aurora-pole-sharp" /></template>
<style>
.buvmeibgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5c3.75-4.75 14.75-4.75 18.5 0M6 20.5h12m-13-9c2.33-2 4.67-2 7 0s4.67 2 7 0M7 15.75c1.67-1.5 3.33-1.5 5 0s3.33 1.5 5 0");
}

</style>
