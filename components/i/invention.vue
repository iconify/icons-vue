<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i1vjpyb9s"/><path class="v6vauh0gy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:invention" /></template>
<style>
.i1vjpyb9s {
  d: path("M9.25 16C7 14.5 5.5 12.5 5.5 9.5a6.5 6.5 0 0 1 13 0c0 3-1.5 5-3.75 6.5Zm.25 2.75h5m-4 2.75h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v6vauh0gy {
  d: path("m11.372 7.339l.052-1.038h1.152l.052 1.038l.929.537l.925-.474l.576.997l-.873.564v1.074l.873.564l-.576.997l-.925-.474l-.929.537l-.052 1.038h-1.152l-.052-1.038l-.929-.537l-.925.474l-.576-.997l.873-.564V8.963l-.873-.564l.576-.997l.925.474Z");
}

</style>
