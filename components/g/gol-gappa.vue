<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="j24fo5bdm"/><path class="cipk5tk9g"/><circle class="rl5edqb6f"/><path class="kp6rbckdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gol-gappa" /></template>
<style>
.cipk5tk9g {
  d: path("M5.75 13.5a2.5 1.5 0 1 0 5 0a2.5 1.5 0 1 0-5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j24fo5bdm {
  cx: 8.25px;
  cy: 15px;
  r: 5.5px;
}

.kp6rbckdv {
  d: path("M15.75 6.25a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0");
}

.rl5edqb6f {
  cx: 17.25px;
  cy: 6.75px;
  r: 4px;
}

</style>
