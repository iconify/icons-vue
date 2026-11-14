<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frd4wxbpv"/><path class="udgjx2soq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:abandoned-bike" /></template>
<style>
.frd4wxbpv {
  d: path("M2.5 8.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m9.25 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.udgjx2soq {
  d: path("M5.75 8.75h4.5l-2-5.25m2 5.25l3-5.25L15 8.75M8.25 3.5h5m2.183 15.792l1.245-2.324a1.5 1.5 0 0 1 2.644 0l1.245 2.324a1.5 1.5 0 0 1-1.322 2.208h-2.49a1.5 1.5 0 0 1-1.322-2.208M18 17.5v1.75");
}

</style>
