<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lj2_ltgfv"/><circle class="nq_6vqa4n"/><path class="nz45sctpe"/></g><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-16" /></template>
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

.lj2_ltgfv {
  d: path("m14.28 22.2l4-2.2m0 0v16");
}

.nq_6vqa4n {
  cx: 29.205px;
  cy: 30.667px;
  r: 5.333px;
}

.nz45sctpe {
  d: path("M33.946 21.975C33.156 20.79 31.773 20 29.6 20h-.395a5.31 5.31 0 0 0-5.333 5.333v5.334");
}

.se87bac5g {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
