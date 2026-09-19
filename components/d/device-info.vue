<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mey8aubmb"/><rect class="ihfajfb1l"/><path class="tgj4p6b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:device-info" /></template>
<style>
.ihfajfb1l {
  width: 21px;
  height: 37px;
  x: 13.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.mey8aubmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.34 15.238l-1.879 1.536l.39 2.395l2.27.86L31 18.493m-4.149.676l-5.702 4.662m-1.489 3.931l1.879-1.536l-.39-2.395l-2.27-.86L17 24.507");
}

.tgj4p6b2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 37.5h21m-8 2.5h-5");
}

</style>
