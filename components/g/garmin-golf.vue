<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s15gkwbmm"/><circle class="c8c-a65gx"/><path class="aqrtfufjp"/><circle class="iss63phpj"/><path class="umrrwdb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:garmin-golf" /></template>
<style>
.aqrtfufjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 8.115a2.68 2.68 0 0 0-2.82-2.678c-1.447.076-2.532 1.377-2.532 2.83v2.484A2.68 2.68 0 0 0 9.5 13.433h0c1.478 0 2.676-1.2 2.676-2.682H9.5");
}

.c8c-a65gx {
  cx: 9.5px;
  cy: 9.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iss63phpj {
  cx: 24px;
  cy: 24.492px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s15gkwbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.176V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4H15.291");
}

.umrrwdb0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.228 33.282c1.418.772 3.044 1.21 4.772 1.21s3.354-.438 4.772-1.21m-3.468-5.467a1.96 1.96 0 0 0 1.322-1.323m1.477 1.827a1.95 1.95 0 0 0 .956-1.607m-4.085 3.325a1.96 1.96 0 0 0 1.756-.644M24 34.492v4.516");
}

</style>
