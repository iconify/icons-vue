<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lj2_ltgfv"/><circle class="nq_6vqa4n"/><path class="nz45sctpe"/></g><g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-simple-16" /></template>
<style>
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

.w5ztvbg7m {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  rx: 4px;
  ry: 4px;
}

.w9v12qzbx {
  d: path("M33.5 4.5v6m-19-6v6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
