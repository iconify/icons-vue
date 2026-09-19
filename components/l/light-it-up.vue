<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="c47dzus1q"/><path class="uj8hlebwy"/><path class="z9uvvi_5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:light-it-up" /></template>
<style>
.c47dzus1q {
  cx: 25.2px;
  cy: 11.9px;
  r: 1.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.uj8hlebwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 35.389l21.45-1.5l.602 8.611m2.383-37l2.923 10.908l9.642-2.083M15.573 27.759c0-2.33 5.993-11.999 8.473-14.479c-3.14 0-5.628 2.006-5.628 2.006l-.71 3.213");
}

.z9uvvi_5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.785 20.734l5.491-1.824l-3.027 3.716l.34 1.17");
}

</style>
