<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pu6af-bnj"/><circle class="gen8q6w5h"/><path class="y0-g8ebfx"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atlas" /></template>
<style>
.gen8q6w5h {
  cx: 15.876px;
  cy: 17.562px;
  r: 1.658px;
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

.pu6af-bnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.353 5.5s.834 5.54 0 11.15c2.55-2.55 2.55 1.856 1.762 6.771s-2.644 6.817-3.85 5.194c.233 6.122-5.471 12.281-7.558 13.885m5.286 0v-6.269m-9.553-18.05c2.55-3.988 5.983-2.272 7.606-.278c-2.574 2.574-5.983 1.113-7.606.278");
}

.y0-g8ebfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.528 15.767c2.54-3.155 4.492-3.235 8.103-1.577m-6.927 5.509c2.594 1.845 5.402 2.808 7.408.802M9.24 17.56s1.34 3.24 1.5 5.56c.16 2.33 3.2 2.6 2.33 4.49c-.54 1.16-1.15 1.13-2.54.7s-1.23.56-2.12.56c-.88 0-.72-.99-2.11-.56c-.3.09-.57.17-.8.21m0-3.95c.32-.39.55-.85.59-1.45c.16-2.32 1.5-5.56 1.5-5.56m17.256 8.865c0-1.179.78-1.387.78-2.531s.087-3.542.71-4.674M5.5 33.85c3.19.95 5.43-.72 8.16-.52m2.216-15.718v-.1");
}

</style>
