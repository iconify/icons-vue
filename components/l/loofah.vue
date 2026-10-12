<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t0abg0byo"/><path class="vc4m6tiby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loofah" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0abg0byo {
  d: path("M4.65 17.63a6.75 5-30 1 1 11.7-6.75a6.75 5-30 1 1-11.7 6.75");
}

.vc4m6tiby {
  d: path("M15.5 9.92c1.39-3.11 3.4-3.12 4.53-1.17s.11 3.69-3.28 3.33m-10.16 2.4c1.44.5.31 2.54 1.75 3.04m1.29-4.79c1.44.5.3 2.54 1.75 3.04m1.28-4.79c1.44.5.31 2.54 1.75 3.04");
}

</style>
