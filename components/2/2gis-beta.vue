<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_ukrubli"/><path class="lwov7sz0s"/><circle class="cfdqkgbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:2gis-beta" /></template>
<style>
.c_ukrubli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.424 34.572L5.598 38.844M42.5 17.416l-10.656-1.68m-13.532-2.133L5.5 11.583m37 21.641V9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h23.895");
}

.cfdqkgbqj {
  cx: 38px;
  cy: 37.913px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lwov7sz0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.462 36.156c.05-4.712-.703-8.98-6.123-8.594a9.76 9.76 0 0 1-2.096-6.042c0-5.389 4.368-9.757 9.757-9.757s9.757 4.368 9.757 9.757a9.64 9.64 0 0 1-2.12 6.042c-5.254-.373-6.138 3.595-6.148 8.111M36.5 38.614a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0m0 1.999v-8");
}

</style>
