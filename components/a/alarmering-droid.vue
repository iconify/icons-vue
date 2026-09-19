<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gv73tqpcb"/><path class="u4kf4w2bl"/><path class="o5r0-obci"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alarmering-droid" /></template>
<style>
.gv73tqpcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.822A5.323 5.323 0 0 0 10.822 5.5M5.5 31.678c14.456 0 26.178-11.722 26.178-26.178M5.5 17.612c6.689 0 12.112-5.423 12.112-12.112");
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

.o5r0-obci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.746c-10.354 0-18.754 8.4-18.754 18.754");
}

.u4kf4w2bl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.254c10.354 0 18.754-8.4 18.754-18.754M42.5 37.178a5.323 5.323 0 0 0-5.321 5.322M42.5 16.322c-14.456 0-26.178 11.721-26.178 26.178M42.5 30.388c-6.689 0-12.112 5.423-12.112 12.112");
}

</style>
