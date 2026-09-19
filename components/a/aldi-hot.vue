<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dt0_d4ygj"/><rect class="j3s9ivbxi"/><path class="udtxwxvxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aldi-hot" /></template>
<style>
.dt0_d4ygj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.875 10.499L14.5 27.501m10.297-17.002l-6.375 17.002m10.297-17.002l-6.375 17.002m7.117-12.752h.871M27.867 19h4.039m-5.632 4.251H33.5");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.udtxwxvxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.451 30.802v8m5.3-8v8m-5.3-4.015h5.3m2.474.715a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0zm4.332-4.7h5.3m-2.65 8v-8");
}

</style>
