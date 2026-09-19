<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="nup6xeblo"/><circle class="pfq2oksba"/><path class="c-71s-b4l"/><circle class="j58usbbuw"/><circle class="ow7lhvbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eneco" /></template>
<style>
.c-71s-b4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.865 28.269c.63.3 1.33.46 2.07.46c2.71 0 4.91-2.2 4.91-4.91s-2.2-4.91-4.91-4.91c-2.38 0-4.35 1.68-4.81 3.92");
}

.j58usbbuw {
  cx: 19.537px;
  cy: 15.033px;
  r: 3.192px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nup6xeblo {
  cx: 19.537px;
  cy: 28.568px;
  r: 7.347px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ow7lhvbwz {
  cx: 25.921px;
  cy: 7.127px;
  r: 2.627px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pfq2oksba {
  cx: 31.821px;
  cy: 39.511px;
  r: 3.989px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
