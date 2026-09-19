<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="m0_qmzbzb"/><circle class="v_scvxebu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doswimmer" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.m0_qmzbzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.24 27.394h14.666c7.96 0 6.331-9.693.18-9.723c-.402-7.116-11.322-8.673-13.44-2.077c-7.227.11-8.371 11.8-1.406 11.8m8.207 5.59l-3.87-1.822l-2.483 3.929m1.062-1.2l2.52 1.173M5.5 35.227h37");
}

.v_scvxebu {
  cx: 15.475px;
  cy: 32.486px;
  r: 1.349px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
