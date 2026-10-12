<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f97t65wtd"/><path class="hrd267kkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dashboard-car" /></template>
<style>
.f97t65wtd {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 6.5px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrd267kkm {
  d: path("M11 12a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-3 0l1.5-1.5M19 12a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-3 0l-1.5-1.5");
}

</style>
