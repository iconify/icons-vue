<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w295u-b2r"/><path class="pqcq4-btq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:format-painter-sharp" /></template>
<style>
.pqcq4-btq {
  d: path("M14.75 5.25h2.5V10h-9.5v3m4.5 8.25l4.5-9l4.5 9m-7.5-3h6M6.25 13h3v8.25h-3z");
}

.w295u-b2r {
  d: path("M2.75 2.75h12v5h-12z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
