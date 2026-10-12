<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qgu-83b5u"/><path class="exhvd4buv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnifier-glass-sharp" /></template>
<style>
.exhvd4buv {
  d: path("M6.25 9.75v-3.5h3.5");
}

.qgu-83b5u {
  d: path("M9.75 2.75a7 7 0 1 1 0 14a7 7 0 1 1 0-14m7.69 12.04l2.47 2.47l1.24 1.24l-1.24 1.24l-.17.17l-1.24 1.24l-1.24-1.24l-2.47-2.47l-1.24-1.24l1.24-1.24l.17-.17l1.24-1.24z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
