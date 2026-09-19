<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="thnf87byf"/><path class="i65yzb6xi"/><path class="h_cmrhbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audio-glow" /></template>
<style>
.h_cmrhbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.7 26.331h7.4v3.306h-7.4zm0-3.306h7.4v3.306h-7.4zm0 6.612h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm7.4-13.224h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm-5.542-13.224h3.684m-11.085-1.653h3.686m11.115-1.434h3.684m-25.884 0h3.684M7.357 11.751h3.686");
}

.i65yzb6xi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.025h7.4v3.306H5.5zm0 3.306h7.4v3.306H5.5zm0 3.306h7.4v3.306H5.5zm0 3.306h7.4v3.306H5.5zm7.4-6.612h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm7.4-13.224h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4zm0 3.306h7.4v3.306h-7.4z");
}

.thnf87byf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.719h7.4v3.306H5.5z");
}

</style>
