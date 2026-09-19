<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n99eamblt"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-21" /></template>
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

.n99eamblt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.482 25.333c0-2.963 2.37-5.333 5.136-5.333s5.333 2.37 5.333 5.333c0 1.383-.592 2.766-1.58 3.753C20.198 30.864 13.482 36 13.482 36h10.47m4.566-13.8l4-2.2m0 0v16");
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
