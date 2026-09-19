<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6bgr1bmp"/><circle class="lrxpa85wh"/><circle class="rb2pgpw4w"/><path class="q4utw1lya"/><path class="iclamcccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jre-wallet" /></template>
<style>
.d6bgr1bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.7H12.3c-4.321 0-7.8-3.729-7.8-8.05s3.479-8.05 7.8-8.05h5.85");
}

.iclamcccv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.788 24.37l3.404-7.727a2.25 2.25 0 0 1 2.966-1.152a2.25 2.25 0 0 1 1.15 2.966L37.87 30.803");
}

.lrxpa85wh {
  cx: 17.9px;
  cy: 13.05px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q4utw1lya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.495 15.49a2.25 2.25 0 0 0-1.15 2.967l5.463 12.4a2.25 2.25 0 1 0 4.117-1.815l-5.464-12.4a2.25 2.25 0 0 0-2.966-1.152m7.922.001a2.25 2.25 0 0 0-1.15 2.967l5.463 12.4a2.25 2.25 0 1 0 4.117-1.815l-5.464-12.4a2.25 2.25 0 0 0-2.966-1.152m-1.551 8.878l1.503-3.411m2.458 5.58l-1.879 4.265");
}

.rb2pgpw4w {
  cx: 10.575px;
  cy: 13.05px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
