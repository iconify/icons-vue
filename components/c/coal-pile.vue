<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d2l5lbczz"/><path class="pli5nub9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coal-pile" /></template>
<style>
.d2l5lbczz {
  d: path("M2.5 17h19M4 17l2-4l2.5-1.5l1.5-3L13 7l2.5 2l2 2l1 2.5L20 17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pli5nub9h {
  d: path("m8.5 11.5l4 1l3-3.5m-3 3.5L12 17");
}

</style>
