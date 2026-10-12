<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="refab6bcg"/><rect class="f_crtvioc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gavel" /></template>
<style>
.f_crtvioc {
  width: 9px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.refab6bcg {
  d: path("M15.28 5.5L13.5 3.72q-.88-.88-1.76 0L5.72 9.74q-.88.88 0 1.76l1.78 1.78q.88.88 1.76 0l6.02-6.02q.88-.88 0-1.76m-2.78 5l7.25 7.25");
}

</style>
