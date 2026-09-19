<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="ra9-be6jm"/><path class="tpk33e88b"/><path class="zbjo9vbzt"/><circle class="x3j1fxvar"/><path class="uq-o6vbrd"/><circle class="rfayv52ni"/><path class="xqgo2ingj"/><path class="xlttwnb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anwb-onderweg" /></template>
<style>
.ra9-be6jm {
  width: 11.656px;
  height: 14.405px;
  x: 4.5px;
  y: 18.038px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.421px;
  ry: 1.421px;
}

.rfayv52ni {
  cx: 28.908px;
  cy: 27.293px;
  r: 0.75px;
  fill: currentColor;
}

.tpk33e88b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 32.442h6.886V16h-7.629v6.872m10.661 9.57h-3.032");
}

.uq-o6vbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.705 21.086a1.57 1.57 0 0 1 1.498 1.098l.476 1.513a1.57 1.57 0 0 0 1.132 1.055l1.104.265c.545.13.93.618.93 1.179v2.87c0 .67-.543 1.212-1.212 1.212h-.952v1.019c0 .85-.69 1.54-1.54 1.54h0c-.85 0-1.54-.69-1.54-1.54v-1.019h-6.2v1.019c0 .85-.69 1.54-1.54 1.54h0a1.54 1.54 0 0 1-1.54-1.54v-1.019h-.952c-.67 0-1.213-.542-1.213-1.212v-2.87c0-.56.385-1.048.93-1.179l1.104-.265a1.57 1.57 0 0 0 1.132-1.055l.476-1.513a1.57 1.57 0 0 1 1.498-1.098z");
}

.x3j1fxvar {
  cx: 20.093px;
  cy: 27.293px;
  r: 0.75px;
  fill: currentColor;
}

.xlttwnb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.343 18.038v-.932c0-1.073-.87-1.943-1.943-1.943h-4.533c-.772 0-1.471.457-1.78 1.165l-.747 1.71M8.803 29.566v-7.77h1.895a1.943 1.943 0 0 1 0 3.884H8.803");
}

.xqgo2ingj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.257 21.086v-1.37c0-.927-.751-1.679-1.678-1.679h-5.821c-.57 0-1.105.281-1.428.751l-1.174 1.706");
}

.zbjo9vbzt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.053 22.634c5.828-1.564 0 6.776 3.743 7.107c3.071.272 4.549-5.97-1.232-10.85m-7.4 1.31h2.148");
}

</style>
