<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dn62scb1l"/><path class="gvd54zfir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googlemail" /></template>
<style>
.dn62scb1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.25 12.227v24.375a2.66 2.66 0 0 1-2.66 2.66h-4.43a1.33 1.33 0 0 1-1.33-1.33V21.488M4.25 12.227v24.375a2.66 2.66 0 0 0 2.66 2.66h4.431a1.33 1.33 0 0 0 1.33-1.33V21.488");
}

.gvd54zfir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.17 9.226a4.21 4.21 0 1 0-5.419 6.446l16.859 14.17a1.77 1.77 0 0 0 2.28 0l16.859-14.17a4.21 4.21 0 0 0-5.418-6.446L23.75 19.801z");
}

</style>
