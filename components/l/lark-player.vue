<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="v0d702f6r"/><circle class="prm3nvx-b"/><rect transform="matrix(-1 0 0 -1 83.956 54.071)" class="sof-ewbxd"/><path class="mt-3r6bpy"/><path class="keh-cxb2v"/><circle class="fky6olbhl"/><path class="t1egbu2-p"/><path class="u_akro3-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lark-player" /></template>
<style>
.fky6olbhl {
  cx: 33.151px;
  cy: 28.362px;
  r: 1.855px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.keh-cxb2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.213 33.586A7.7 7.7 0 0 1 24 35.24a7.7 7.7 0 0 1-4.213-1.654");
}

.mt-3r6bpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.932 6.692a18.38 18.38 0 0 1 16.86 13.756M24 37.034c2.518 0 4.213-3.448 4.213-3.448S26.106 30.45 24 30.45s-4.213 3.136-4.213 3.136s1.695 3.448 4.213 3.448");
}

.prm3nvx-b {
  cx: 14.849px;
  cy: 28.362px;
  r: 1.855px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sof-ewbxd {
  width: 5.044px;
  height: 13.102px;
  x: 39.456px;
  y: 20.485px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.159px;
}

.t1egbu2-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.234 20.988c-2.288-6.514-8.342-10.441-12.706-11.974l.005-.001A13.84 13.84 0 0 0 13.85 4.73s5.077.655 7.632 3.275a12.04 12.04 0 0 0-10.973 1.008s4.762-1.524 8.606.535c-4.183 1.813-9.29 5.579-11.349 11.439m.297 11.791C11.329 40.544 20.264 43.642 24 43.642s12.67-3.097 15.936-10.863");
}

.u_akro3-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.875 8.559a18.4 18.4 0 0 0-9.668 11.89");
}

.v0d702f6r {
  width: 5.044px;
  height: 13.102px;
  x: 3.5px;
  y: 20.485px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.159px;
}

</style>
