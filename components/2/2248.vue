<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="qy8a8dzsd"/><rect class="ieznx5rfm"/><rect class="cm_xiujcg"/><rect class="n7959htri"/><path class="h2jxpc_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:2248" /></template>
<style>
.cm_xiujcg {
  width: 18.5px;
  height: 18.5px;
  x: 24px;
  y: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.h2jxpc_0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.805 38.25l-.001-10l-5.366 6.717h6.625m-6.625-21.904a3.313 3.313 0 0 1 6.624 0a3.1 3.1 0 0 1-.97 2.342c-1.34 1.176-5.654 4.345-5.654 4.345h6.625m11.874-6.687a3.313 3.313 0 0 1 6.625 0a3.1 3.1 0 0 1-.97 2.342c-1.34 1.176-5.655 4.345-5.655 4.345h6.625m-4.124 13.5a2.5 2.5 0 0 0 0 5h1.624a2.5 2.5 0 0 0 0-5m.001 0a2.5 2.5 0 0 0 0-5h-1.626a2.5 2.5 0 0 0 0 5m.001 0h1.625");
}

.ieznx5rfm {
  width: 18.5px;
  height: 18.5px;
  x: 5.5px;
  y: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.n7959htri {
  width: 18.5px;
  height: 18.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qy8a8dzsd {
  width: 18.5px;
  height: 18.5px;
  x: 24px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
