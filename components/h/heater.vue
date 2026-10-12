<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ntf2xjbnm"/><rect class="dwquvob_c"/><path class="m8dwpsa-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heater" /></template>
<style>
.dwquvob_c {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8dwpsa-v {
  d: path("M7.5 9.75v6m4.5-6v6m4.5-6v6m-10.5 3v2.5m12-2.5v2.5");
}

.ntf2xjbnm {
  d: path("M8 2.75v1.5m4-1.5v1.5m4-1.5v1.5");
}

</style>
