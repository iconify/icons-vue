<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wj_4jpbgb"/><path class="x3mqa04pb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-shuffle" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj_4jpbgb {
  d: path("m2.781 10.785l6.358-1.351l2.08 9.781l-6.358 1.351Zm12.08-1.351l6.358 1.351l-2.08 9.781l-6.358-1.351ZM6 6.5a7 7 0 0 1 12 0");
}

.x3mqa04pb {
  d: path("M18.5 4L18 6.5l-2.5-.75");
}

</style>
