<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hhycw79tw"/><path class="j61jpyc9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-arrow-return" /></template>
<style>
.hhycw79tw {
  width: 14.5px;
  height: 12px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j61jpyc9x {
  d: path("m6 10.75l3.65 2.75c.8.6 1.9.6 2.7 0L16 10.75m1.5-8L15.25 5l2.25 2.25M15.25 5h3.5a2.5 2.5 0 0 1 2.5 2.5v1.75");
}

</style>
