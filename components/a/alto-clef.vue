<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pwo6nabbc"/><path class="dgyeu7ets"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alto-clef" /></template>
<style>
.dgyeu7ets {
  d: path("M10.75 2.75v18.5m2.25-17c.9-.95 2-1.5 3.25-1.5c1.8 0 3 1.6 3 3.75c0 2.5-1.6 4-3.6 4c-1 0-1.9-.6-2.4-1.5l-2.5 3l2.5 3c.5-.9 1.4-1.5 2.4-1.5c2 0 3.6 1.5 3.6 4c0 2.15-1.2 3.75-3 3.75c-1.25 0-2.35-.55-3.25-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pwo6nabbc {
  width: 3px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 0.75px;
}

</style>
