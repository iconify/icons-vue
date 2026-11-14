<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dyjdpzbjq"/><path class="c_5tqqnoz"/><path class="d9_yerbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-scooter" /></template>
<style>
.c_5tqqnoz {
  d: path("M5.5 17H8l3-9h2");
}

.d9_yerbmd {
  d: path("m11 8l3 9h2M15 6h2.5l1 11");
}

.dyjdpzbjq {
  d: path("M3 17a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm13 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
