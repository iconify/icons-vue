<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><rect class="c4gqxkyyo"/><path class="gc-566cwe"/><path class="l-e2lpudy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:classroom" /></template>
<style>
.c4gqxkyyo {
  width: 31px;
  height: 23.2px;
  x: 8.5px;
  y: 12.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.gc-566cwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.68 33.41h6.62v2.19h-6.62zM25.84 19a2.6 2.6 0 0 0-3.677-.003L22.16 19a2.61 2.61 0 1 0 4.46 1.86a2.54 2.54 0 0 0-.8-1.86zM22 25.53h4a3 3 0 0 1 3 3v1.21H19v-1.21a3 3 0 0 1 3-3m-4.58-4.06a2 2 0 0 0-2.828-.012l-.012.012A2 2 0 1 0 18 22.91a2 2 0 0 0-.6-1.43z");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.l-e2lpudy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.34 27.14a2 2 0 0 0-1.47-.65h-3.74a2 2 0 0 0-2 2v1.25H19m14.42-8.27a2 2 0 0 0-2.828-.012l-.012.012A2 2 0 1 0 34 22.91a2 2 0 0 0-.6-1.43zM29 29.74h6.86v-1.25a2 2 0 0 0-2-2h-3.73a2 2 0 0 0-1.47.65");
}

</style>
