<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nngloju6h"/><rect class="w81nkrbfl"/><path class="meu9bmglu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:haveli" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.meu9bmglu {
  d: path("M5.75 12.5V11a1.25 1.25 0 0 1 2.5 0v1.5Zm10 0V11a1.25 1.25 0 0 1 2.5 0v1.5ZM9.5 21.25v-5a2.5 2.5 0 0 1 5 0v5Z");
}

.nngloju6h {
  d: path("M4.25 6.5a1.5 3 0 0 1 3 0m9.5 0a1.5 3 0 0 1 3 0M9.5 6.5a2.5 3 0 0 1 5 0");
}

.w81nkrbfl {
  width: 17.5px;
  height: 14.75px;
  x: 3.25px;
  y: 6.5px;
  rx: 1px;
}

</style>
