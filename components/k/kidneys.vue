<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v2dwsobrv"/><path class="rd31a7b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kidneys" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rd31a7b1j {
  d: path("M15.5 13h2.25c1.5 0 2.5 1 2.5 2.5v5.75");
}

.v2dwsobrv {
  d: path("M15 4.5c-3.5-2.5-9.75-.75-10.25 6C4.25 17 9.5 21 13.5 19.75c2.5-.75 2.5-3.5 1-5c-1-1-1-2.5 0-3.5c1.75-1.75 2.75-4.75.5-6.75");
}

</style>
