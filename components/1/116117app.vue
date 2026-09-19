<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="hueeutb6d"/><circle class="g2gmrbyiw"/><path class="tu0n9zczt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:116117app" /></template>
<style>
.g2gmrbyiw {
  cx: 30.855px;
  cy: 18.942px;
  r: 3.191px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hueeutb6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.954 13.811l2.408-1.311v9.632m4.389-8.321l2.408-1.311v9.632m-9.205 5.047l2.408-1.311V35.5m4.389-8.321l2.408-1.311V35.5m5.704 0l5.183-9.632h-6.381");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.tu0n9zczt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.764 13.675c-.532-.696-1.342-1.175-2.685-1.175h-.224a3.19 3.19 0 0 0-3.19 3.19v3.251");
}

</style>
