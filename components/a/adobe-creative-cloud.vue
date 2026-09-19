<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="bd5so5bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-creative-cloud" /></template>
<style>
.bd5so5bzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.28 33.616c-2.97.107-4.786.276-7.286-1.37a7.97 7.97 0 0 1 5.784-14.456c2.915.503 5.133 3.077 7.601 6.144m-5.193-7.626a9.8 9.8 0 0 1 2.009-1.217a9.57 9.57 0 0 1 13.304 8.753a9.5 9.5 0 0 1-.575 3.382a8.8 8.8 0 0 1-1.53 2.77a9.46 9.46 0 0 1-9.05 3.482c-3.597-.603-6.445-3.928-9.67-7.448");
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

</style>
