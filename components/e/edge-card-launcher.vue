<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="gmjinsb0j"/><path class="fyv6n3ptt"/><path class="mqx4myb4e"/><path class="zvw75npai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edge-card-launcher" /></template>
<style>
.fyv6n3ptt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.067 36.813v3.931c0 .97.786 1.756 1.756 1.756h24.7c.97 0 1.755-.786 1.755-1.756V7.256c0-.97-.786-1.756-1.756-1.756h-24.7c-.969 0-1.755.786-1.755 1.756v3.93");
}

.gmjinsb0j {
  width: 31.166px;
  height: 25.627px;
  x: 5.722px;
  y: 11.187px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.756px;
  ry: 1.756px;
}

.mqx4myb4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.454 11.187h-3.11c-.97 0-1.756.786-1.756 1.756v22.114c0 .97.786 1.756 1.756 1.756h3.11m5.85-25.626h-3.11c-.97 0-1.756.786-1.756 1.756v22.114c0 .97.787 1.756 1.756 1.756h3.11");
}

.zvw75npai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.66 18.129h-8.306a2.345 2.345 0 0 0-2.345 2.344v.61m10.651 8.862h-8.306a2.345 2.345 0 0 1-2.345-2.345v-1.218a2.345 2.345 0 0 1 2.345-2.345h8.306");
}

</style>
