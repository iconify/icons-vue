<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yx09k6b3t"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-movies" /></template>
<style>
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

.yx09k6b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.14 11H12c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 12 16h-1.86a1.57 1.57 0 0 1-1.57-1.57v-1.82A1.57 1.57 0 0 1 10.14 11M36 11h1.86c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 37.86 16H36a1.57 1.57 0 0 1-1.57-1.57v-1.82A1.57 1.57 0 0 1 36 11m-25.86 7H12c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 12 23h-1.86a1.57 1.57 0 0 1-1.57-1.57v-1.85A1.57 1.57 0 0 1 10.13 18zM36 18h1.86c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 37.86 23H36a1.57 1.57 0 0 1-1.57-1.57v-1.85A1.57 1.57 0 0 1 35.99 18zm-25.86 7H12c.867 0 1.57.703 1.57 1.57v1.85A1.57 1.57 0 0 1 12.01 30h-1.87a1.57 1.57 0 0 1-1.57-1.57v-1.87A1.57 1.57 0 0 1 10.14 25M36 25h1.86c.867 0 1.57.703 1.57 1.57v1.85A1.57 1.57 0 0 1 37.87 30H36a1.57 1.57 0 0 1-1.57-1.57v-1.87A1.57 1.57 0 0 1 36 25m-25.86 7H12c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 12 37h-1.86a1.57 1.57 0 0 1-1.57-1.57v-1.9A1.57 1.57 0 0 1 10.14 32M36 32h1.86c.867 0 1.57.703 1.57 1.57v1.86A1.57 1.57 0 0 1 37.86 37H36a1.57 1.57 0 0 1-1.57-1.57v-1.9A1.57 1.57 0 0 1 36 32");
}

</style>
