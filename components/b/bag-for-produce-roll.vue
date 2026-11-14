<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kytgkt5wk"/><path class="gclptsris"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bag-for-produce-roll" /></template>
<style>
.gclptsris {
  d: path("M3.5 4.75V17a3.5 1.75 0 0 0 7 0V4.75m0 3.75h10V21L18 19.75L15.5 21L13 19.75L10.5 21v-4");
}

.kytgkt5wk {
  d: path("M3.5 4.75a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
