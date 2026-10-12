<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cq6nxphjg"/><rect class="r6-o0bcpk"/><path class="fknzpccmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jailbreak-lock" /></template>
<style>
.cq6nxphjg {
  d: path("M8 10.25v-3.5a4 4 0 0 1 8 0v.5");
}

.fknzpccmd {
  d: path("m12.5 12.75l-1.75 2.75l2.5 1.5l-1.75 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6-o0bcpk {
  width: 14.5px;
  height: 11px;
  x: 4.75px;
  y: 10.25px;
  rx: 2.5px;
}

</style>
