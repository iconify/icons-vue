<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ec7t6absc"/><path class="whiy3isnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lip-gloss" /></template>
<style>
.ec7t6absc {
  width: 5.5px;
  height: 12px;
  x: 4.25px;
  y: 9.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whiy3isnh {
  d: path("M7 12.5v5m9.75-7l-.63-5.84a2.4 2.4 0 1 1 4.56 1.48Zm-.15.5l-1.4 4.4m-.78.66l.96.3q.95.31.64 1.26L15.26 20q-.31.95-1.26.64l-.96-.3q-.95-.31-.64-1.26l.76-2.38q.31-.95 1.26-.64");
}

</style>
