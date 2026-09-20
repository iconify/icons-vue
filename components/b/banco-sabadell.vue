<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yfwwnrg-r"/><path class="pazrirp_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banco-sabadell" /></template>
<style>
.pazrirp_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.365 35.393c1.54 1.952 3.47 2.678 6.155 2.678h3.717c3.459 0 6.263-2.73 6.263-6.097v-.026c0-3.368-2.804-6.098-6.263-6.098h-4.1c-3.462 0-6.27-2.733-6.27-6.103c0-3.379 2.814-6.118 6.284-6.118h3.696c2.686 0 4.616.727 6.156 2.678m-27.886 1.551a2.114 2.114 0 1 1 0 4.23h-3.49v-8.459h3.49a2.114 2.114 0 1 1 0 4.23m0-.001h-3.485");
}

.yfwwnrg-r {
  cx: 13.43px;
  cy: 17.858px;
  r: 7.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
