<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="pb1ni7_hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:floating-counter" /></template>
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

.pb1ni7_hc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.815 32.028a5.32 5.32 0 0 1-4.627 2.702c-2.943 0-5.329-2.402-5.329-5.365v-3.488c0-2.963 2.386-5.365 5.329-5.365a5.32 5.32 0 0 1 4.622 2.693M16.345 34.731V17.025c0-2.074 1.67-3.756 3.73-3.756c1.836 0 2.982.548 3.768 1.572m-10.658 5.672h7.46");
}

</style>
