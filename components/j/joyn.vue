<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="gj5y7kglt"/><path class="cgarpybgb"/><path class="x_gh5rxbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:joyn" /></template>
<style>
.cgarpybgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 17.75h2.967v9.762A2.764 2.764 0 0 1 9.5 30.287M24.334 17.75v5.152c0 1.451 2.107 3.94 5.456 1.116");
}

.gj5y7kglt {
  cx: 18.257px;
  cy: 21.386px;
  r: 3.637px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.x_gh5rxbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.79 17.75v9.857c0 3.637-5.456 3.063-5.456.479m8.328-10.337v7.557m0-4.686c1.531-2.87 5.838-4.306 5.838-1.052v5.738");
}

</style>
