<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g-0y4pbch"/><circle class="fmyt52i2x"/><circle class="ix0sepbgl"/><circle class="s-dxozb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hail-sharp" /></template>
<style>
.fmyt52i2x {
  cx: 8px;
  cy: 18px;
  r: 1.5px;
}

.g-0y4pbch {
  d: path("M7.51 13.89a3.52 3.52 0 0 1-.49-7.01a5.06 5.06 0 0 1 9.38-1.22a3.96 3.96 0 0 1-.53 8.23Z");
}

.ix0sepbgl {
  cx: 12px;
  cy: 19.5px;
  r: 1.5px;
}

.s-dxozb8l {
  cx: 16px;
  cy: 18px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
