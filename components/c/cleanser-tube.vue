<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ry9s8lr0o"/><path class="hr42q26km"/><path class="i8njtcg0g"/><rect class="bbp_00r1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cleanser-tube" /></template>
<style>
.bbp_00r1u {
  width: 7px;
  height: 2.75px;
  x: 8.5px;
  y: 18.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.hr42q26km {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 9.75a1.5 1.5 0 1 1-3 0a1.5 1.5 0 1 1 3 0");
}

.i8njtcg0g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 12.5h.01");
}

.ry9s8lr0o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h10.5q1 0 .85.99l-1.45 9.27q-.15.99-.95 1.59l-.4.3q-.8.6-1.8.6h-3q-1 0-1.8-.6l-.4-.3q-.8-.6-.95-1.59L5.9 3.74q-.15-.99.85-.99m-.5 2.5h11.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
