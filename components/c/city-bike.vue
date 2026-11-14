<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zcy6llb4i"/><path class="mmh5q-f0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-bike" /></template>
<style>
.mmh5q-f0k {
  d: path("M6 15.5h5.5q1.5-7 5-7.5l1.5 7.5M16.5 8l-.25-2.5h2.5m-7.25 10l-1-7.5M9 8h3m5 2a5.5 5.5 0 0 1 4.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcy6llb4i {
  d: path("M2.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm-12-4.5a5.5 5.5 0 0 1 5-.75");
}

</style>
