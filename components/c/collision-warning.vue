<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hoyfhcbmf"/><path class="slylwsbnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:collision-warning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoyfhcbmf {
  d: path("M2.75 16.25v-2.5q0-1 .97-1.24l.06-.02q.97-.24 1.32-1.18l.8-2.12q.35-.94 1.35-.94h3q1 0 1.55.83l1.4 2.09q.55.83 1.51 1.12l.58.17q.96.29.96 1.29v2.5q0 1-1 1H3.75q-1 0-1-1m2-4h9");
}

.slylwsbnw {
  d: path("M5 17.25a1.75 1.75 0 0 0 3.5 0m2.25 0a1.75 1.75 0 0 0 3.5 0m5-7.5l2-1.75m-2 5.5h2m-2 3.75l2 1.75");
}

</style>
