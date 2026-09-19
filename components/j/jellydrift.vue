<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="osa58cjui"/><path class="v-1fqviji"/><circle class="molt9nhia"/><circle class="uj3kkccco"/><path class="igzw-gm1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jellydrift" /></template>
<style>
.igzw-gm1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.039 17.249l5.967-2.541m-12.885 2.541l5.967-2.541m6.359 8.866l5.967-2.542m6.119 8.699l5.967-2.542m-5.967-1.074l5.967-2.541");
}

.molt9nhia {
  cx: 8.38px;
  cy: 30.642px;
  r: 2.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.osa58cjui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.85 23.574h13.597v6.96H11.85zm-6.117 6.96h-.669L4.5 28.88v-5.306h7.35v6.96h-.82m20.843 0h1.715l3.945-.803v-3.753s-3.79-2.404-12.086-2.404v6.96h1.131m-6.539-13.285h-6.918l-1.271 6.325h13.597l-.868-1.015zM43.5 27.19v-3.754s-3.789-2.404-12.086-2.404m0 0l-.868-1.014l-4.539-5.31h-6.919");
}

.uj3kkccco {
  cx: 29.226px;
  cy: 30.642px;
  r: 2.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v-1fqviji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 23.574v-1.889l8.621-4.436");
}

</style>
