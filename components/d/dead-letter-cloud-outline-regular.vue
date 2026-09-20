<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sk-a6mb_r"/><path class="t-ce5gbrd"/><path class="nn04ptkrq"/><path class="myf7-9gbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dead-letter-cloud-outline-regular" /></template>
<style>
.myf7-9gbi {
  d: path("m19 19 -3 3");
}

.nn04ptkrq {
  d: path("m16 19 3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sk-a6mb_r {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.t-ce5gbrd {
  d: path("m6 7 6 6 6 -6");
}

</style>
