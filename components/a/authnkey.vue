<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="f_xy96zlh"/><path class="bv7h57bqg"/><circle class="gbgzu0b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:authnkey" /></template>
<style>
.bv7h57bqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.063 35.787v5.975c0 .96.778 1.738 1.738 1.738h6.398c.96 0 1.738-.778 1.738-1.738v-5.975");
}

.f_xy96zlh {
  width: 20.858px;
  height: 31.287px;
  x: 13.571px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.485px;
  ry: 3.485px;
}

.gbgzu0b7q {
  cx: 23.825px;
  cy: 20.143px;
  r: 4.149px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
