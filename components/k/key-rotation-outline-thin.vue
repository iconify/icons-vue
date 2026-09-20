<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="u2z_81bft"/><path class="p8m79mb4i"/><path class="m2xst7buy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:key-rotation-outline-thin" /></template>
<style>
.d8z1r1beo {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2xst7buy {
  d: path("m13 10.5 2 2");
}

.p8m79mb4i {
  d: path("m11 12.5 4 -4");
}

.u2z_81bft {
  d: path("M7.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wzx0dxb2r {
  d: path("m12 2 3 3 -3 3");
}

</style>
