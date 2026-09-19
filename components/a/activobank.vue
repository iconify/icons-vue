<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="fpfchqauo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:activobank" /></template>
<style>
.fpfchqauo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 32.822V26.92h8.822v5.902m0-5.902l-2.97-11.742h-2.875L13.5 26.92M31.559 24h-4.974m0-8.822h4.457a2.94 2.94 0 0 1 2.94 2.94v2.941A2.94 2.94 0 0 1 31.043 24h.517a2.94 2.94 0 0 1 2.94 2.94v2.941a2.94 2.94 0 0 1-2.94 2.941h-4.974m-.001-17.644v17.644");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

</style>
