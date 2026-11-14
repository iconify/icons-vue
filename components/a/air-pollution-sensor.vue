<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r1pm1vbkz"/><path class="x79lbbbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-pollution-sensor" /></template>
<style>
.r1pm1vbkz {
  d: path("M7 3h10v9H7Zm5 9v9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x79lbbbgh {
  d: path("M10.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3.5 5h.01m16.99-.5h.01M4 10.5h.01M20 11h.01");
}

</style>
