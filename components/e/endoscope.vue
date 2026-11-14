<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="olt8kmb1r"/><path class="jzeijzd4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:endoscope" /></template>
<style>
.jzeijzd4h {
  d: path("M15 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1.5 0h.01");
}

.olt8kmb1r {
  d: path("M2.5 14h5v7.5h-5ZM5 14c0-7 4.5-10 8.25-5.5m0 2.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
