<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d95imwosb"/><rect class="obnguabsq"/><path class="nuw7y5bow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laptop-and-phone" /></template>
<style>
.d95imwosb {
  d: path("M5.75 3.75h12q2 0 2 1.75t-2 1.75h-3q-2 0-2 2v3.5q0 2-2 2h-5q-2 0-2-2v-7q0-2 2-2m-3 14.5h9.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nuw7y5bow {
  d: path("M17.75 18.5h1.5");
}

.obnguabsq {
  width: 5.5px;
  height: 11px;
  x: 15.75px;
  y: 10.25px;
  rx: 1.5px;
}

</style>
