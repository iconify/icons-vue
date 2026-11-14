<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phal6y-gi"/><path class="vtkg7lbxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-tube" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.phal6y-gi {
  d: path("M7.25 9.5v2.25a4.75 4.75 0 1 0 3 0V9.5m-2.5-3h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 6.25 8a1.5 1.5 0 0 1 1.5-1.5");
}

.vtkg7lbxg {
  d: path("M8.75 6.5v-2a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2V19");
}

</style>
