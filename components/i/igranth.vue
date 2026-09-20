<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ezzbt-2ju"/><circle class="jlq5g-bed"/><path class="apgetqb4l"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:igranth" /></template>
<style>
.apgetqb4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.255 23.112v4.708m21.841-6.174v5.285c0 .49.397.888.888.888h.266m-2.087-4.707h1.865m-8.309 2.931a1.776 1.776 0 0 1-3.553 0v-1.155a1.776 1.776 0 0 1 3.553 0m0 2.932v-4.708m5.275 4.708v-2.932a1.776 1.776 0 0 0-3.553 0m0 2.932v-4.708m-9.696-.044a2.354 2.354 0 1 0-4.708 0v2.398a2.354 2.354 0 1 0 4.708 0H14.39");
}

.ezzbt-2ju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.947 20.714v7.106m0-2.932a1.776 1.776 0 0 1 3.553 0v2.932m-20.114-2.932c0-.98.795-1.776 1.777-1.776m-1.777 0v4.708");
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

.jlq5g-bed {
  cx: 10.255px;
  cy: 20.936px;
  r: 0.755px;
  fill: currentColor;
}

</style>
