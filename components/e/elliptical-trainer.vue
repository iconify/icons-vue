<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f4x3joxaq"/><path class="h9p-fpbil"/><circle class="u1kwaccfz"/><circle class="i3uvqeq4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elliptical-trainer" /></template>
<style>
.f4x3joxaq {
  cx: 18px;
  cy: 17.25px;
  r: 3.25px;
}

.h9p-fpbil {
  d: path("m18 14l-1.75-5.75m0 0l3.25-5.5m-3.25 5.5l-4.5-5m-1.09 12.53a4.5 2.25 0 0 1-4.43 3.66m-2.39-.72a4.5 2.25 0 0 1 4.43-3.66");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3uvqeq4b {
  cx: 5px;
  cy: 19.2px;
  r: 1.25px;
}

.u1kwaccfz {
  cx: 9.5px;
  cy: 15.3px;
  r: 1.25px;
}

</style>
