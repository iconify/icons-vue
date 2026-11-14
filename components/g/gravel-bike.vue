<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m5ogao32u"/><path class="chcnyrbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gravel-bike" /></template>
<style>
.chcnyrbhq {
  d: path("m6 14l3.5-5h5L12 14Zm8.5-5l3.5 5m-3.5-5V5H17a1.25 1.25 0 0 1 0 2.5m-14.5 13h6l1.5-1l1.5 1h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m5ogao32u {
  d: path("M2.5 14a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
