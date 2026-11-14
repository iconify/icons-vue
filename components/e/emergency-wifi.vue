<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ti88u0brw"/><path class="pzyfl9k4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-wifi" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pzyfl9k4x {
  d: path("M3.5 8.5a10.5 10.5 0 0 1 15 0m0 5l3.5 1.25v2.75c0 2.5-1.75 4-3.5 4.5c-1.75-.5-3.5-2-3.5-4.5v-2.75Z");
}

.ti88u0brw {
  d: path("M11 16h.01M8.5 13.5q.102-.104.213-.2t.229-.182t.243-.161q.125-.076.256-.141t.267-.119t.276-.097t.283-.073t.288-.049t.291-.025t.292-.001t.292.024t.288.048t.283.072t.276.095q.137.053.268.118q.131.064.256.14M6 11a7 7 0 0 1 10 0");
}

</style>
