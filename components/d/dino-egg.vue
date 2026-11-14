<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxgngabqp"/><path class="idx0akzwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dino-egg" /></template>
<style>
.cxgngabqp {
  d: path("M5 12a7 9.5 0 1 0 14 0a7 9.5 0 1 0-14 0Z");
}

.idx0akzwx {
  d: path("M5.5 8.5L8 7l2 2.5L12.5 7l2 2.5l2.25-2l1.75 1m-9 6.5h.01m4.99 1.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
