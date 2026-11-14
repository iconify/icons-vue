<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cttfzlbpm"/><path class="bcm-xab8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-today" /></template>
<style>
.bcm-xab8u {
  d: path("M11.75 8.25a4.25 4.25 0 1 1 5.5 4.25m-8-3V13M16 2v1m5.5 5.5h.5m-2-4l.75-.75M20 12.5l.75.75");
}

.cttfzlbpm {
  d: path("M5.125 9.5h8.25A2.625 2.625 0 0 1 16 12.125v6.75a2.625 2.625 0 0 1-2.625 2.625h-8.25A2.625 2.625 0 0 1 2.5 18.875v-6.75A2.625 2.625 0 0 1 5.125 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
