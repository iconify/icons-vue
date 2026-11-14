<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpot37r8w"/><path class="zorunob7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kilogram" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpot37r8w {
  d: path("M7.435 8h9.13a1.75 1.75 0 0 1 1.716 1.407l1.8 9a1.75 1.75 0 0 1-1.716 2.093H5.635a1.75 1.75 0 0 1-1.716-2.093l1.8-9A1.75 1.75 0 0 1 7.435 8");
}

.zorunob7v {
  d: path("M9.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
