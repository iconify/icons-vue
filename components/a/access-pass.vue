<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgwtqfb_x"/><path class="kk_x44bns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-pass" /></template>
<style>
.cgwtqfb_x {
  d: path("M2.5 6.5h19v13h-19Zm7 0v-3h5v3");
}

.kk_x44bns {
  d: path("M6.25 11a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM5 16.75c0-1.5 1.25-2.25 3-2.25s3 .75 3 2.25M13.5 13h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
