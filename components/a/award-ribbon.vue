<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ia7_lf06s"/><circle class="u782pnb2p"/><path class="d-4s68bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:award-ribbon" /></template>
<style>
.d-4s68bnx {
  d: path("M10.9 9.1L7.75 20.75M13.1 9.1l3.15 11.65");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ia7_lf06s {
  d: path("M9.14 6.68L4.11 4.07Q3 3.5 3 4.75v5q0 1.25 1.11.68l5.03-2.61q1.11-.57 0-1.14m5.72 0l5.03-2.61Q21 3.5 21 4.75v5q0 1.25-1.11.68l-5.03-2.61q-1.11-.57 0-1.14");
}

.u782pnb2p {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
}

</style>
