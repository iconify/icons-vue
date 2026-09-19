<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5lz2hz7x"/><rect class="gbgak59_z"/><path class="h1_royt0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autotagger" /></template>
<style>
.gbgak59_z {
  width: 21.8px;
  height: 10.57px;
  x: 12.78px;
  y: 18.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.28px;
}

.h1_royt0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.07 18.72H4.5m0 2.14v-4.29m29.61 9.6l9.39 8V13.83l-9.39 8.01");
}

.t5lz2hz7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.9 18.72v13.15m4.93-13.15v13.15m-6.36-13.15v-4.1m8.43 4.1v-4.1m-4.22 4.1v-4.1m-7.29 0h14.59");
}

</style>
