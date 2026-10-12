<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jnb1024rj"/><path class="wpaf79bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:foundation-pile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnb1024rj {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 1px;
}

.wpaf79bkk {
  d: path("M4.75 8.25h2.5V19.5L6 21.25L4.75 19.5Zm6 0h2.5V19.5L12 21.25l-1.25-1.75Zm6 0h2.5V19.5L18 21.25l-1.25-1.75Zm-14 5.25h.5m5.5 0h.5m5.5 0h.5m5.5 0h.5");
}

</style>
