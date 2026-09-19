<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h5lvx4bqj"/><path class="ppenu2d_c"/><circle class="kxf3kcbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:agora-ai" /></template>
<style>
.h5lvx4bqj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m5.5 42.5l9.25-37h6.68l-9.25 37z");
}

.kxf3kcbdw {
  cx: 24px;
  cy: 27.597px;
  r: 2.056px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.ppenu2d_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.57 5.5h6.68l9.25 37h-6.68z");
}

</style>
