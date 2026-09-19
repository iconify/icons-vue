<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="v9cca2fby"/><path class="bcwx_zbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clipeus" /></template>
<style>
.bcwx_zbtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.793 31.793L16.207 16.207");
}

.v9cca2fby {
  width: 34.383px;
  height: 22.041px;
  x: 6.808px;
  y: 12.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.5px;
  ry: 3.5px;
}

</style>
