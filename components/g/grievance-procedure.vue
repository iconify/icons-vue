<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zv9fz7bdu"/><path class="o9urw486i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grievance-procedure" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9urw486i {
  d: path("M17.25 7.75L19 9.5l1.75-1.75");
}

.zv9fz7bdu {
  d: path("m7 2.5l1.5 1.75l2.5.25l-.5 2.25l1.25 1.75l-2 1.25l-.5 2.25L7 11l-3 2.75l.25-4l-2-1.25L3.5 6.75L3 4.5l2.5-.25ZM12.5 15a2.5 2.5 0 0 1 2.5-2.5h4a2.5 2.5 0 0 1 2.5 2.5v2a2.5 2.5 0 0 1-2.5 2.5h-3.5l-3 2Zm2-10.5c3 0 4.5 1.5 4.5 4.75");
}

</style>
