<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ye76jactu"/><path class="h16xshl5p"/><path class="ehzp3we8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drawstring" /></template>
<style>
.ehzp3we8h {
  d: path("M9.5 9c0 4-2 6-2 11.5m7-11.5c0 4 2 6 2 11.5");
}

.h16xshl5p {
  d: path("M8.25 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ye76jactu {
  d: path("M2.5 3.5c5.5 1.25 13.5 1.25 19 0v7c-5.5 1.25-13.5 1.25-19 0Z");
}

</style>
