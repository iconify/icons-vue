<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d88eypbro"/><circle class="xxox8_56p"/><circle class="swaygxr7p"/><path class="fdrzylb5q"/><path class="mf1syzwpv"/><circle class="h97gn6bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fennec" /></template>
<style>
.d88eypbro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.05L7.2 6.61a1.77 1.77 0 0 0-2.7 1.5v22ZM7.2 6.61l9.16 15.54");
}

.fdrzylb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.05l-19.5 13L22.4 41.2a3 3 0 0 0 3.2 0l17.9-11.12Z");
}

.h97gn6bdv {
  cx: 29.86px;
  cy: 30.54px;
  r: 1.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mf1syzwpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.05L40.8 6.61a1.77 1.77 0 0 1 2.7 1.5v22ZM40.8 6.61l-9.16 15.54");
}

.swaygxr7p {
  cx: 24px;
  cy: 39.44px;
  r: 2.22px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xxox8_56p {
  cx: 18.14px;
  cy: 30.54px;
  r: 1.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
