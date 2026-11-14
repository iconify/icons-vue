<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rk28bfblz"/><path class="xbic4eb6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rk28bfblz {
  d: path("M3.25 4.75a1.5 2.25 0 1 0 3 0a1.5 2.25 0 1 0-3 0");
}

.xbic4eb6v {
  d: path("M4.75 2.5h14.5a1.5 2.25 0 0 1 0 4.5H4.75M4.5 9.75V21.5m15-11.75V21.5M2 21.5h20m-14-6h7M12.5 13l2.5 2.5l-2.5 2.5");
}

</style>
