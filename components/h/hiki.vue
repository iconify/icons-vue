<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="voevzcb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hiki" /></template>
<style>
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

.voevzcb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.206L16.224 42.5M5.5 33.675L16.224 42.5M5.71 14.963l29.18-1.532M38.85 5.5L22.775 37.69M34.89 13.431l7.61 9.775M24.893 36.135L42.5 38.088M15.047 14.472l6.43 24.171M5.5 28.755l9.547-14.283M7.054 6.336l7.993 8.136m16.745 5.162c1.675-3.354-1.185-5.848-3.681-5.848s-5.41 1.597-5.41 3.616c-.841-1.99-1.706-3.242-3.844-3.13c-3.161.166-2.687 4.419-2.053 6.805");
}

</style>
