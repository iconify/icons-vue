<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jg0acgbpj"/><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-30" /></template>
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

.jg0acgbpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.541 30.667c0 2.963 2.37 5.333 5.333 5.333s5.136-2.37 5.136-5.333v-5.334c0-2.963-2.37-5.333-5.136-5.333s-5.333 2.37-5.333 5.333zm-13.549 4.111c1.104.926 2.297 1.35 4.975 1.35h.624a4 4 0 0 0 3.999-4h0a4 4 0 0 0-4-3.998m-5.6-6.666c1.107-.922 2.3-1.343 4.979-1.336l.622.004a4 4 0 0 1 3.999 3.999h0a4 4 0 0 1-4 3.999m-3.073 0h3.074");
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
