<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l7ty2tb7b"/><rect class="xyzy125ow"/><path class="styqm-bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hitachi-healthy-chef" /></template>
<style>
.l7ty2tb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 17h33v14h-33z");
}

.styqm-bwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.208 12.793L35.915 6.5h-23.83l-6.293 6.293M5.5 38h37m-35-23h33");
}

.xyzy125ow {
  width: 37px;
  height: 29px;
  x: 5.5px;
  y: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
