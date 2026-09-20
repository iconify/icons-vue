<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:long-polling-outline-thin" /></template>
<style>
.bxa1b1bso {
  d: path("M6 5v14");
}

.fr472ib_x {
  d: path("m13 16 3 3 3 -3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7g1r9bby {
  d: path("M16 5v14");
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
