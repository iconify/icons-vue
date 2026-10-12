<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr3heeyhc"/><rect class="e4_x2-bzv"/><path class="x74i0jbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:defibrillator" /></template>
<style>
.e4_x2-bzv {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 5.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x74i0jbzi {
  d: path("M8.75 17.5c-2.5-1.75-3.5-3.25-3.5-5.25a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0c0 2-1 3.5-3.5 5.25m8.75-8l-2.5 4h3.5l-2.5 4");
}

.zr3heeyhc {
  d: path("M8.5 5.75v-1.5a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5");
}

</style>
