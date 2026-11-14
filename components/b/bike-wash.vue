<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sx5sr-pck"/><path class="ik7n1dbod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-wash" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik7n1dbod {
  d: path("M6 17.75h5.5L15 12.5H9.75l1.75 5.25M15 12.5l3 5.25m-3-5.25l-.5-2h2.25M6 2.5L7.5 5a1.5 1.5 0 0 1-3 0Zm6 0L13.5 5a1.5 1.5 0 0 1-3 0Zm6 0L19.5 5a1.5 1.5 0 0 1-3 0Z");
}

.sx5sr-pck {
  d: path("M2.75 17.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
