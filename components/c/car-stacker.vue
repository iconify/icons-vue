<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1fvkkb-t"/><path class="c55-rqbyd"/><path class="yv6lk9brp"/><path class="gmnksypjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-stacker" /></template>
<style>
.c55-rqbyd {
  d: path("M5.5 8.5v-1l2-.5l1.75-1.75h5.5L16.5 7l2 .5v1Z");
}

.gmnksypjc {
  d: path("M6.25 19.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1fvkkb-t {
  d: path("M2.5 2.5v19h19v-19M2.5 12h19");
}

.yv6lk9brp {
  d: path("M6.25 10.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5.5 18v-1l2-.5l1.75-1.75h5.5l1.75 1.75l2 .5v1Z");
}

</style>
