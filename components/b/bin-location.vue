<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="d3_o15ttj"/><path class="vx4fhtbnh"/><path class="o6a500beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bin-location" /></template>
<style>
.d3_o15ttj {
  width: 15.5px;
  height: 7.5px;
  x: 4.25px;
  y: 13.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.vx4fhtbnh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.5h4.5M12 11C9.83 8.83 8.75 7.58 8.75 6a3.25 3.25 0 0 1 6.5 0c0 1.58-1.08 2.83-3.25 5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
