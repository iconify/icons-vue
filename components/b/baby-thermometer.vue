<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7947ab6x"/><circle class="fxwnb7vgp"/><path class="hspgb-b5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-thermometer" /></template>
<style>
.fxwnb7vgp {
  cx: 5px;
  cy: 19px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hspgb-b5j {
  d: path("m12 12l2.5-2.5");
}

.r7947ab6x {
  d: path("m8.23 12.23l7.5-7.5a2.5 2.5 0 0 1 3.54 3.54l-7.5 7.5a2.5 2.5 0 0 1-3.54-3.54m0 3.54l-1.82 1.82");
}

</style>
