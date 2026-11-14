<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rc1g9kzzv"/><path class="fp3zhlbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bug-alert" /></template>
<style>
.fp3zhlbzq {
  d: path("M7.25 8.5a2.5 2.5 0 0 1 4.5 0M2.5 11l3 1m11-1l-3 1m-11 3l3-.5m11 .5l-3-.5M3 19l2.75-1.75M18 15v3.25M18 21h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rc1g9kzzv {
  d: path("M5.5 13.25a4 5.25 0 1 0 8 0a4 5.25 0 1 0-8 0");
}

</style>
