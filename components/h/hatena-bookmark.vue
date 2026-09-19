<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="yfq6fg0bf"/><path class="fui_0dfxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hatena-bookmark" /></template>
<style>
.fui_0dfxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.404 24c2.022 0 3.661 1.65 3.661 3.688s-1.639 3.687-3.661 3.687h-6.041v-14.75h6.041c2.022 0 3.661 1.65 3.661 3.688S24.426 24 22.404 24m0 0H16.37m15.018-7.375v10.97");
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

.yfq6fg0bf {
  cx: 31.388px;
  cy: 31.375px;
  r: 0.75px;
  fill: currentColor;
}

</style>
