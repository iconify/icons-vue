<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pirkrbbnc"/><path class="h9u4-bbds"/><circle class="bo05k8tmp"/><circle class="vfl2_8dlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:applemusic" /></template>
<style>
.bo05k8tmp {
  cx: 12.27px;
  cy: 38.68px;
  r: 4.82px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h9u4-bbds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.08 19.57a2.16 2.16 0 0 1 1.75-2.13L38 13.69a2.16 2.16 0 0 1 2.58 2.12m-.03-2.16v18.56M17.08 18.25v20.43");
}

.pirkrbbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.08 18.25v-7.83a2.16 2.16 0 0 1 1.75-2.13L38 4.54a2.16 2.16 0 0 1 2.58 2.13v7");
}

.vfl2_8dlf {
  cx: 35.73px;
  cy: 32.21px;
  r: 4.82px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
