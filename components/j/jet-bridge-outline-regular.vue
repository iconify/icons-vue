<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw5kuce7r"/><path class="czysiurpc"/><path class="yg08zkbcc"/><path class="ah-zd_bma"/><path class="i699y-pkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jet-bridge-outline-regular" /></template>
<style>
.ah-zd_bma {
  d: path("M13 9v7");
}

.czysiurpc {
  d: path("M3 9h15v7H3");
}

.i699y-pkg {
  d: path("M21 6v13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uw5kuce7r {
  d: path("M3 3v18");
}

.yg08zkbcc {
  d: path("M8 9v7");
}

</style>
