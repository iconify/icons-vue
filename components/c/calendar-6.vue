<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="x5hwmfx5f"/><path class="m4wtvmses"/></g><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-6" /></template>
<style>
.brxpxfbzn {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

.bybjau59l {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
}

.m4wtvmses {
  d: path("M28.74 21.975C27.95 20.79 26.569 20 24.396 20H24a5.31 5.31 0 0 0-5.333 5.333v5.334");
}

.se87bac5g {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

.x5hwmfx5f {
  cx: 24px;
  cy: 30.667px;
  r: 5.333px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
