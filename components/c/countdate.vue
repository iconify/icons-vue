<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ywp4ipkrn"/><rect class="jnd4jbbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:countdate" /></template>
<style>
.jnd4jbbga {
  width: 35.641px;
  height: 35.641px;
  x: 6.179px;
  y: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ywp4ipkrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.096 26.575l-3.5 1.925m0 0v-14m-3.417 1.225c-1.05-.875-1.925-1.225-4.2-1.225h-.525c-2.45 0-4.55 2.1-4.55 4.55s2.1 4.55 4.55 4.55h4.725v4.9h-9.275m18.279 8.742V43m-22.366-5.758V43");
}

</style>
