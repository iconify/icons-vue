<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d6gtv7b3x"/><rect class="qoaajrbra"/><path class="d0wn0vb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:edge-ai" /></template>
<style>
.d0wn0vb3x {
  d: path("M17.25 15q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25q-.27-1.98-2.25-2.25q1.98-.27 2.25-2.25");
}

.d6gtv7b3x {
  d: path("M4.95 11.31a2.2 2.2 0 0 1-.3-4.38a3.16 3.16 0 0 1 5.86-.76a2.48 2.48 0 0 1-.33 5.14ZM8 13.75v1.5a2 2 0 0 0 2 2h1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qoaajrbra {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 13.25px;
  rx: 2px;
}

</style>
