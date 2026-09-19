<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hdfigjbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leobank" /></template>
<style>
.hdfigjbkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.067 17.917v12.166h5.968m14.915-8.061c1.648 0 2.983 1.362 2.983 3.042v1.977c0 1.68-1.336 3.041-2.983 3.041h0c-1.648 0-2.984-1.362-2.984-3.041v-1.977c0-1.68 1.336-3.042 2.984-3.042m-6.357 6.526A2.97 2.97 0 0 1 24 30.083c-1.648 0-2.983-1.362-2.983-3.042v-1.977c0-1.68 1.335-3.041 2.983-3.041s2.984 1.361 2.984 3.041v.989h-5.967");
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

</style>
