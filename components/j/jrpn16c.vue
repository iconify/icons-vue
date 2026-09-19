<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="x_5qm0bxj"/><circle class="m25l51-kr"/><path class="jaba7zrts"/><circle class="h-vh2cb2w"/><path class="gw1sywbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jrpn16c" /></template>
<style>
.gw1sywbbm {
  d: path("M26.145 36.482c-.396-.593-1.088-.989-2.175-.989h-.198c-1.483 0-2.669 1.186-2.669 2.57v2.768");
}

.h-vh2cb2w {
  cx: 23.772px;
  cy: 40.831px;
  r: 2.669px;
}

.jaba7zrts {
  d: path("m15.392 36.484l1.977-1.087v8.007m17.549-2.765a2.66 2.66 0 0 1-2.67 2.669h0c-1.482 0-2.668-1.186-2.668-2.57v-2.67c0-1.482 1.186-2.668 2.669-2.57h0a2.55 2.55 0 0 1 2.57 2.57h0");
}

.m25l51-kr {
  cx: 29.085px;
  cy: 23.131px;
  r: 2.201px;
}

.x_5qm0bxj {
  cx: 24px;
  cy: 16.926px;
  r: 12.426px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
