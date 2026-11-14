<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gklh5nbwm"/><path class="f1drx5bjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:affiliate-code" /></template>
<style>
.f1drx5bjv {
  d: path("M6.25 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m6.25 4.5l5.5-9M13 9h.01m4.49 6h.01");
}

.gklh5nbwm {
  d: path("m3.99 10.281l4.225-4.875a2.63 2.63 0 0 1 1.984-.906h8.176A2.625 2.625 0 0 1 21 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-8.176a2.63 2.63 0 0 1-1.984-.906L3.99 13.719a2.625 2.625 0 0 1 0-3.438");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
