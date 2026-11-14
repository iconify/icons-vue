<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5r5rjb6d"/><path class="aozaq4bdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-archive" /></template>
<style>
.aozaq4bdg {
  d: path("M13.5 3v4.5H18m-8.5 8h5");
}

.i5r5rjb6d {
  d: path("M3 11v8a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-8M2.5 11h19M6 11V4.5A1.5 1.5 0 0 1 7.5 3h6L18 7.5V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
