<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m6kkv_bev"/><path class="rnbphpbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-routing" /></template>
<style>
.m6kkv_bev {
  d: path("M2.5 7.5A2.5 2.5 0 0 1 5 5h6a2.5 2.5 0 0 1 2.5 2.5V13a2.5 2.5 0 0 1-2.5 2.5H8.5l-3 3v-3H5A2.5 2.5 0 0 1 2.5 13Zm11 2.5h3l4-4m-4 4l4 4");
}

.rnbphpbjs {
  d: path("M18 6h2.5v2.5m0 3V14H18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
