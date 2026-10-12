<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbma36-1e"/><rect class="uphyiwc0c"/><path class="r1dti4fkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barber-pole" /></template>
<style>
.hbma36-1e {
  d: path("M8.75 5.5C8.75 4 10.2 2.75 12 2.75S15.25 4 15.25 5.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1dti4fkr {
  d: path("M8.75 13.25L13.5 8.5m-3 7.75l4.75-4.75m-7.5 8.75h8.5");
}

.uphyiwc0c {
  width: 6.5px;
  height: 7.75px;
  x: 8.75px;
  y: 8.5px;
  rx: 1px;
}

</style>
