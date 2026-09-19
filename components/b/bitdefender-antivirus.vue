<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zrdco8k5v"/><path class="x4afujshd"/><path class="y47ys9bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitdefender-antivirus" /></template>
<style>
.x4afujshd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5c16.65-7.85 15.05-21.05 15.05-23.45v-7.6L24 5.5L8.95 11.45v7.6c0 2.4-1.6 15.6 15.05 23.45");
}

.y47ys9bmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.45 21.547c12.6-4.847 23.701-6.192 25.75-1.497c1.15 2.635-4.6 5.9-4.6 5.9");
}

.zrdco8k5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.95 30.9c-11.495 3.65-21.1 5.245-23.15.55c-1.15-2.635 4.57-5.759 4.57-5.759");
}

</style>
