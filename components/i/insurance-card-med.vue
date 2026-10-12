<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="wiwu8ob3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insurance-card-med" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la5qfrrxr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

.wiwu8ob3f {
  d: path("m8.25 8.25l3 1V12c0 2-1.4 3.25-3 3.75c-1.6-.5-3-1.75-3-3.75V9.25Zm0 2.25v3M6.75 12h3m3.75-2h4.75m-4.75 3h3.25");
}

</style>
