<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><rect class="zff1mybez"/><path class="pple9cc9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:claro-movel" /></template>
<style>
.pple9cc9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.142 26.15a2.1 2.1 0 0 1 2.101-2.101h0m-2.101 0v5.568m-8.097-8.405v8.405m6.108-2.101a2.1 2.1 0 0 1-2.102 2.1h0a2.1 2.1 0 0 1-2.1-2.1V26.15a2.1 2.1 0 0 1 2.1-2.101h0c1.16 0 2.102.94 2.102 2.1m-.001 3.468v-5.568m-8.084 2.749v.035a2.784 2.784 0 0 1-2.784 2.784h0A2.784 2.784 0 0 1 9.5 26.833v-2.837a2.784 2.784 0 0 1 2.784-2.784h0a2.784 2.784 0 0 1 2.784 2.784v.034m15.665-2.083v-3.564m3.168 4.941l3.152-3.152m-2.117 6.661H38.5");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.zff1mybez {
  width: 4.202px;
  height: 5.568px;
  x: 28.632px;
  y: 24.049px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.101px;
  ry: 2.101px;
}

</style>
