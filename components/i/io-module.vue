<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpgpyib4r"/><path class="f3anvhbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:io-module" /></template>
<style>
.f3anvhbxq {
  d: path("M8.75 10.25L10.5 12l-1.75 1.75M13.5 12h8m-1.75-1.75L21.5 12l-1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpgpyib4r {
  d: path("M5.5 3.5H17v17H5.5Zm-3 8.5h8");
}

</style>
