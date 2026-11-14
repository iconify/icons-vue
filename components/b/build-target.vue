<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6pfebmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build-target" /></template>
<style>
.yd6pfebmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm8-9.75v3.5m0 12.5v3.5M2.25 12h3.5m12.5 0h3.5M12 12h.01");
}

</style>
