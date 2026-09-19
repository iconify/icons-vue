<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7lwq5v4d"/><circle class="jlq5g-bed"/><path class="o-_he0e_p"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:igranth" /></template>
<style>
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

.o-_he0e_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.255 23.112v4.708m21.841-6.174v5.285c0 .49.397.888.888.888h.266m-2.087-4.707h1.865m-8.309 2.931c0 .981-.796 1.776-1.777 1.776h0a1.776 1.776 0 0 1-1.776-1.776v-1.155c0-.98.795-1.776 1.776-1.776h0c.981 0 1.777.795 1.777 1.776m0 2.932v-4.708m5.275 4.708v-2.932c0-.98-.795-1.776-1.776-1.776h0c-.981 0-1.776.795-1.776 1.776m-.001 2.932v-4.708m-9.696-.044c0-1.3-1.054-2.354-2.354-2.354h0a2.354 2.354 0 0 0-2.354 2.354v2.398c0 1.3 1.054 2.354 2.354 2.354h0c1.3 0 2.354-1.054 2.354-2.354H14.39");
}

.o7lwq5v4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.947 20.714v7.106m0-2.932c0-.98.795-1.776 1.776-1.776h0c.982 0 1.777.795 1.777 1.776v2.931m-20.114-2.931c0-.98.795-1.776 1.777-1.776h0m-1.777 0v4.708");
}

</style>
