<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m18cr1byt"/><path class="x216ecbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-steward" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m18cr1byt {
  d: path("M12.672 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.544 0 1.065.048M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 6.75l3.25 1.25V18c0 1.9-1.35 3.1-3.25 3.75c-1.9-.65-3.25-1.85-3.25-3.75v-2.5Z");
}

.x216ecbyc {
  d: path("m16.5 18l1 1l2-2");
}

</style>
