<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="culm9zbxu"/><path class="xzeqa83-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-arsenic" /></template>
<style>
.culm9zbxu {
  d: path("m3 13l4-8l8-1.5L21 9l-1 8l-8 3.5l-7.5-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzeqa83-v {
  d: path("M8 12q.5-4 4.5-4.75");
}

</style>
