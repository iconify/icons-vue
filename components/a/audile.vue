<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="iavtnqbjc"/><path class="n4v15e86w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audile" /></template>
<style>
.iavtnqbjc {
  cx: 24px;
  cy: 37.298px;
  r: 2.239px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n4v15e86w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.153 38.067a7.863 7.863 0 0 0 7.129-7.846v-1.584h-8.788a1.785 1.785 0 1 1 0-3.57h8.788v-3.544h-8.788a1.785 1.785 0 1 1 0-3.57h8.788V14.41h-8.788a1.785 1.785 0 1 1 0-3.57l8.638-.003A7.864 7.864 0 0 0 29.4 4.5H18.6a7.864 7.864 0 0 0-7.732 6.337l8.638.003a1.785 1.785 0 1 1 0 3.57h-8.788v3.543h8.788a1.785 1.785 0 1 1 0 3.57h-8.788v3.543h8.788a1.785 1.785 0 1 1 0 3.57h-8.788v1.585a7.863 7.863 0 0 0 7.129 7.846a6.2 6.2 0 0 0 12.306 0");
}

</style>
