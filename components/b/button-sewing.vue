<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="djkl9lb1y"/><path class="s48ygeb4z"/><path class="la6-kmmne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:button-sewing" /></template>
<style>
.djkl9lb1y {
  d: path("m3 3l2.25 1.25L7.5 3l2.25 1.25L12 3l2.25 1.25L16.5 3l2.25 1.25L21 3l-1.25 2.25L21 7.5l-1.25 2.25L21 12l-1.25 2.25L21 16.5l-1.25 2.25L21 21l-2.25-1.25L16.5 21l-2.25-1.25L12 21l-2.25-1.25L7.5 21l-2.25-1.25L3 21l1.25-2.25L3 16.5l1.25-2.25L3 12l1.25-2.25L3 7.5l1.25-2.25Z");
}

.la6-kmmne {
  d: path("M10 13q2-3.5 4 0");
}

.s48ygeb4z {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm3 1h.01M14 13h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
