<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e392g-b1e"/><path class="x7-q6xbdo"/><path class="wc-0c0b-l"/><path class="h9uy-z23d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chain-fork" /></template>
<style>
.e392g-b1e {
  d: path("m12 13.5l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

.h9uy-z23d {
  d: path("m15 4.5l3.5 2l3.5-2m-3.5 2v4m-13 0l6.5 3l6.5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wc-0c0b-l {
  d: path("m2 4.5l3.5 2l3.5-2m-3.5 2v4m13-8l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

.x7-q6xbdo {
  d: path("m8.5 15.5l3.5 2l3.5-2m-3.5 2v4m-6.5-19l3.5 2v4l-3.5 2l-3.5-2v-4Z");
}

</style>
