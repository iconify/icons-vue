<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="uxtih1yxo"/><path class="be59kb4pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:insta-eclipse" /></template>
<style>
.be59kb4pk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.25 24c0 4.56-3.69 8.25-8.25 8.25s-8.25-3.69-8.25-8.25s3.69-8.25 8.25-8.25c.59 0 1.17.06 1.72.18c-.76.8-1.22 1.88-1.22 3.07c0 2.49 2.01 4.5 4.5 4.5c1.19 0 2.27-.46 3.07-1.22c.12.55.18 1.13.18 1.72");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.uxtih1yxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 19c0 1.3-.55 2.47-1.43 3.28c-.8.76-1.88 1.22-3.07 1.22c-2.49 0-4.5-2.01-4.5-4.5c0-1.19.46-2.27 1.22-3.07c.81-.88 1.98-1.43 3.28-1.43c2.49 0 4.5 2.01 4.5 4.5");
}

</style>
