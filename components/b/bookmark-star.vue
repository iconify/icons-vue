<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_os4qq9l"/><path class="ubxk6uiie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bookmark-star" /></template>
<style>
.m_os4qq9l {
  d: path("M6 3h12v18l-6-4.5L6 21Z");
}

.ubxk6uiie {
  d: path("m12 6l1.029 2.334l2.537.257l-1.902 1.7l.54 2.493L12 11.5l-2.204 1.284l.54-2.493l-1.902-1.7l2.537-.257Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
