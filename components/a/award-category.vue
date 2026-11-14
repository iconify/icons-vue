<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_vfh8bil"/><path class="ceqr-6wjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:award-category" /></template>
<style>
.c_vfh8bil {
  d: path("M3.5 7.75a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ceqr-6wjb {
  d: path("m5 10.75l-1 5l3-1.5l3 1.5l-1-5m5-3h6.5m-6.5 6h6.5m-17 6h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
