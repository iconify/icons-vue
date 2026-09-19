<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfw9b-b-i"/><rect class="qd3aopg1w"/><path class="gg7qv6b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:b-hyve" /></template>
<style>
.gg7qv6b7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.428 16.245v16.779");
}

.qd3aopg1w {
  width: 12.051px;
  height: 11.499px;
  x: 18.408px;
  y: 20.953px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.885px;
  ry: 0.885px;
}

.xfw9b-b-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.983 32.94c-2.65-4.486-4.892-8.344-4.98-8.575s2.066-4.253 4.787-8.939l4.949-8.52l20.304.007L44 24.1l-9.957 16.967l-20.24.026z");
}

</style>
