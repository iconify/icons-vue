<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sj-2z92uf"/><path class="dzpym8b4f"/><rect class="x2cgfaclh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:basket-full" /></template>
<style>
.dzpym8b4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 19.5h.01m7.99 0h.01");
}

.sj-2z92uf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h1.4A1.5 1.5 0 0 1 5.61 7.9l1.79 7.85M6 9.25h13.5a1 1 0 0 1 .97 1.24l-.95 3.8a2 2 0 0 1-1.94 1.46H7.4Z");
}

.x2cgfaclh {
  width: 6px;
  height: 3.25px;
  x: 10px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
