<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ufmxn6a_t"/><path class="m9me6bb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-shape" /></template>
<style>
.m9me6bb5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

.ufmxn6a_t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h2.5q1.5 0 1.5 1.5v1q0 1.5 1.5 1.5H18q1.5 0 1.5 1.5v2.5q0 1.5-1.5 1.5h-1.75q-1.5 0-1.5 1.5v6q0 1.5-1.5 1.5h-2.5q-1.5 0-1.5-1.5v-6q0-1.5-1.5-1.5H6q-1.5 0-1.5-1.5v-2.5q0-1.5 1.5-1.5h1.75q1.5 0 1.5-1.5v-1q0-1.5 1.5-1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
