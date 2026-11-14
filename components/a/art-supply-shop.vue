<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsjqhoq0r"/><path class="rlrv5acmk"/><path class="o9tthgb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:art-supply-shop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o9tthgb6i {
  d: path("M8 20.5v-5h4v5m3 1l2.75-2.75m-1-1l2 2c2-2 2.75-3.5 3-4.75c-1.25.25-2.75 1-5 2.75");
}

.rlrv5acmk {
  d: path("M5.25 10.75v9.75h7.15m6.35-7.35v-2.4");
}

.tsjqhoq0r {
  d: path("m3 8.5l1.5-5h15l1.5 5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0");
}

</style>
