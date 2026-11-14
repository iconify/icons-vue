<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xbvsxtbcq"/><path class="hd42ibc_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bungalow" /></template>
<style>
.hd42ibc_r {
  d: path("M9.5 11.5V8L12 5.5L14.5 8v3.5m-4 10v-4h3v4m-7-6h1m9 0h1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbvsxtbcq {
  d: path("M2.5 11.5L7 3h10l4.5 8.5Zm1.5 0v10h16v-10");
}

</style>
