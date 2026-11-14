<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cr2inp7zq"/><path class="mgy8-lbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hourglass-ancient" /></template>
<style>
.cr2inp7zq {
  d: path("M2.5 14.5a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

.mgy8-lbph {
  d: path("m16 14.5l-4-10v10h4m-4 0l-5.5 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
