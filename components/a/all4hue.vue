<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="f1f5cnbiu"/><path class="mak6658vp"/><rect class="nfzli_bgg"/><path class="ms-j6-_1p"/><rect class="ge54flbkp"/><path class="oman2bbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:all4hue" /></template>
<style>
.f1f5cnbiu {
  width: 10.93px;
  height: 16.52px;
  x: 32.57px;
  y: 24.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.33px;
}

.ge54flbkp {
  width: 10.93px;
  height: 16.52px;
  x: 4.5px;
  y: 24.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.33px;
}

.mak6658vp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.54 27.74v10m0-5h3.24m-3.24-5h4.99m-4.99 10h4.99");
}

.ms-j6-_1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.75 27.75v6.62a3.25 3.25 0 1 0 6.5 0v-6.62");
}

.nfzli_bgg {
  width: 10.93px;
  height: 16.52px;
  x: 18.53px;
  y: 24.48px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.33px;
}

.oman2bbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.66 32.74h6.62m0-5v10M6.45 27.43v10.62M23.79 7v12.23m-8.08 0v-8.1m0 5.04a3.05 3.05 0 0 1-3 3.06h0a3.05 3.05 0 0 1-3-3.06v-2a3 3 0 0 1 3-3h0a3 3 0 0 1 3 3m22.28 5.06V7l-6.51 8.25h8.02M19.62 7v12.23");
}

</style>
