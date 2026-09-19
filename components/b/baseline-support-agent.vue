<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytwguvegx"/><circle class="po6vlitvx"/><circle class="alqc54g4m"/><path class="nwtbv1bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-support-agent" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.nwtbv1bng {
  fill: currentColor;
  d: path("M18 11.03A6.04 6.04 0 0 0 12.05 6c-3.03 0-6.29 2.51-6.03 6.45a8.07 8.07 0 0 0 4.86-5.89c1.31 2.63 4 4.44 7.12 4.47");
}

.po6vlitvx {
  cx: 9px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.ytwguvegx {
  fill: currentColor;
  d: path("M21 12.22C21 6.73 16.74 3 12 3c-4.69 0-9 3.65-9 9.28c-.6.34-1 .98-1 1.72v2c0 1.1.9 2 2 2h1v-6.1c0-3.87 3.13-7 7-7s7 3.13 7 7V19h-8v2h8c1.1 0 2-.9 2-2v-1.22c.59-.31 1-.92 1-1.64v-2.3c0-.7-.41-1.31-1-1.62");
}

</style>
