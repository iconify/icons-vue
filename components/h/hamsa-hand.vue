<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hi3ae_g6n"/><path class="f0bx-2b8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hamsa-hand" /></template>
<style>
.f0bx-2b8x {
  d: path("M8.75 15.75c1.75-2.25 4.75-2.25 6.5 0c-1.75 2.25-4.75 2.25-6.5 0");
}

.hi3ae_g6n {
  d: path("M5.75 15v-4.5a1.25 1.25 0 0 1 2.5 0V6.25a1.25 1.25 0 0 1 2.5 0V5a1.25 1.25 0 0 1 2.5 0v1.25a1.25 1.25 0 0 1 2.5 0v4.25a1.25 1.25 0 0 1 2.5 0V15c0 3.5-2.75 6-6.25 6s-6.25-2.5-6.25-6m2.5-4.5v2.25m2.5-6.5v4.5m2.5-4.5v4.5m2.5-.25v2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
