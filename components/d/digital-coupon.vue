<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qily9sb1s"/><path class="d3jigzxnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-coupon" /></template>
<style>
.d3jigzxnt {
  d: path("M8.75 9h6.5v2a1 1 0 0 0 0 2v2h-6.5v-2a1 1 0 0 0 0-2Z");
}

.qily9sb1s {
  d: path("M6 2.5h12v19H6Zm4.5 2.75h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
