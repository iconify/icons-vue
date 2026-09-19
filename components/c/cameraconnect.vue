<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wy4wshb6x"/><circle class="xvbb-_bbu"/><path class="kipximsri"/><path class="swg7f5xkl"/><ellipse class="h87jz7b_c"/><path class="bb_d6t_fj"/><path class="p8z-e6j4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cameraconnect" /></template>
<style>
.bb_d6t_fj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24.111c-.164-3.673-4.205-3.397-5.436-3.76c0 0-2.73-4.259-3.805-4.328a52.5 52.5 0 0 0-7.134-.095c-1.37.145-3.425 4.233-3.425 4.233l-2.187.19a4.12 4.12 0 0 0-2.758-.856c-1.331.165-2.657 2.027-3.187 2.093c-1.535.19-3.364 1.033-3.374 2.523m1.844-17.15A9.543 9.543 0 0 1 4.5 16.5");
}

.h87jz7b_c {
  cx: 30.776px;
  cy: 30.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.002px;
  ry: 7.958px;
}

.kipximsri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.044 25.627a4.86 4.86 0 0 1 3.53 3.544");
}

.p8z-e6j4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.093 6.961A13.6 13.6 0 0 1 4.5 20.555M9.85 6.961a5.353 5.353 0 0 1-5.35 5.35");
}

.swg7f5xkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.194 24.144v13.568a1.844 1.844 0 0 0 1.844 1.842h11.484c3.687 1.861 7.326 2.095 10.896 0h5.239a1.844 1.844 0 0 0 1.843-1.842v-13.6");
}

.wy4wshb6x {
  cx: 16.626px;
  cy: 24.179px;
  r: 0.75px;
  fill: currentColor;
}

.xvbb-_bbu {
  cx: 30.863px;
  cy: 30.333px;
  r: 3.015px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
