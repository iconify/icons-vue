<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="li-y2pbdd"/><path class="xbzax3b5i"/><path class="a614robba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-check" /></template>
<style>
.a614robba {
  d: path("m5.5 9.25l4-5H14m-3.25 5l-1.5-6M8 3.25h2.5m3.5 1l-.5-1.5h1.75M14.75 18l2 2L21 15.75");
}

.li-y2pbdd {
  d: path("M2.5 9.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbzax3b5i {
  d: path("M5.5 9.25h5.25l3.25-5l2.5 5");
}

</style>
