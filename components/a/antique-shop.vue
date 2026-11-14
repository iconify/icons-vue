<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsjqhoq0r"/><path class="xdkxoofmo"/><path class="kxcdqacba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antique-shop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxcdqacba {
  d: path("M8 20.5v-5h4v5m3.75-6.75h5l-1.5 1.75c2.25 1 2.5 2.75 2.25 4s-1.25 2-3.25 2s-3-.75-3.25-2s0-3 2.25-4Z");
}

.tsjqhoq0r {
  d: path("m3 8.5l1.5-5h15l1.5 5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0");
}

.xdkxoofmo {
  d: path("M5.25 10.75v9.75h7.15");
}

</style>
