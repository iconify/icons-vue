<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0zgbkb8i"/><path class="ty4srebww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple-bag" /></template>
<style>
.q0zgbkb8i {
  d: path("M10.262 8.052L10.5 4h10l1 17h-8.171M10.25 7.5h10.5m-14.879.584A3.77 3.77 0 0 0 3.75 7.75q.034.342.111.653");
}

.ty4srebww {
  d: path("M8 11.5c-2-1.25-5-.75-5 3C3 18 5.5 21 8 20.25c2.5.75 5-2.25 5-5.75c0-3.75-3-4.25-5-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
