<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uz149n6rs"/><path class="kgycf273o"/><path class="m1qj1mbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-motorcycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgycf273o {
  fill: currentColor;
  d: path("M9 10c0-2.5 3-3 5.5-1.75l1 2.25H9Z");
}

.m1qj1mbjh {
  d: path("M11.25 11.5h2a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m-6.5 5.75l5-1.75m-5 1.75h.01m14.49 0h.01");
}

.uz149n6rs {
  d: path("M2 17.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m14.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75 0L16.5 6.5m0 0l-2.25-2M3.5 9.5H9");
}

</style>
