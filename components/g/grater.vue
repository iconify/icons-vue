<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fq0q99btn"/><path class="tg2oxlu1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grater" /></template>
<style>
.fq0q99btn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.75h7q1.5 0 1.68 1.49l1.39 11.52q.18 1.49-1.32 1.49H6.75q-1.5 0-1.32-1.49L6.82 8.24Q7 6.75 8.5 6.75m1 0v-2.5a1.5 1.5 0 0 1 1.5-1.5h2a1.5 1.5 0 0 1 1.5 1.5v2.5");
}

.tg2oxlu1e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10.75h.01m3.99 0h.01m-4.26 3.5h.01m4.49 0h.01m-4.76 3.5h.01m4.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
