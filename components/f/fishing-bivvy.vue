<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3n7k4rmk"/><path class="m91odid_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fishing-bivvy" /></template>
<style>
.m91odid_d {
  d: path("M8.5 19.5c0-5 1.5-7.5 3.5-7.5s3.5 2.5 3.5 7.5");
}

.n3n7k4rmk {
  d: path("M3.5 19.5c0-9 4-14.5 8.5-14.5s8.5 5.5 8.5 14.5M2 19.5h20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
