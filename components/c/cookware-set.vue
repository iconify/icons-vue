<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lltwh51jd"/><rect class="pmk16i_zx"/><path class="m9b8te44h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cookware-set" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lltwh51jd {
  d: path("M4.75 6.75a4.25 2.25 0 0 1 8.5 0ZM9 4.5V2.75");
}

.m9b8te44h {
  d: path("M2.75 17.25h12.5v.5a3.5 3.5 0 0 1-3.5 3.5h-5.5a3.5 3.5 0 0 1-3.5-3.5Zm12.5 1h6");
}

.pmk16i_zx {
  width: 8.5px;
  height: 7px;
  x: 4.75px;
  y: 6.75px;
  rx: 1.75px;
}

</style>
