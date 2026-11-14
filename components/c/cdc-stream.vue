<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9ephnlrl"/><path class="m-aeb6ber"/><path class="g8ret4h-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cdc-stream" /></template>
<style>
.g8ret4h-u {
  d: path("M2.5 12a5 2.5 0 0 0 10 0m3 0h6m-3-3l3 3l-3 3");
}

.l9ephnlrl {
  d: path("M2.5 6a5 2.5 0 1 0 10 0a5 2.5 0 1 0-10 0Z");
}

.m-aeb6ber {
  d: path("M2.5 6v12a5 2.5 0 0 0 10 0V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
