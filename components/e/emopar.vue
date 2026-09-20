<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y88bn1bgl"/><circle class="wqt--tncc"/><circle class="qzkl2mfrp"/><circle class="sudduaclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emopar" /></template>
<style>
.qzkl2mfrp {
  cx: 24.05px;
  cy: 12.169px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sudduaclq {
  cx: 30.2px;
  cy: 6.7px;
  r: 2.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wqt--tncc {
  cx: 14px;
  cy: 40px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y88bn1bgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.872 18.152c-2.343-2.343-5.984-2.501-8.132-.353L24 21.539l-3.74-3.74c-2.148-2.148-5.788-1.99-8.132.353s-2.5 5.984-.353 8.132L24 38.509l12.225-12.225c2.148-2.148 1.99-5.789-.354-8.132Z");
}

</style>
