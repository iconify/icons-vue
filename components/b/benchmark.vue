<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xl5onfbxd"/><path class="yj2kwourk"/><path class="xlrgsobgu"/><path class="rl29muolu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:benchmark" /></template>
<style>
.rl29muolu {
  fill: currentColor;
  d: path("M10.75 16.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xl5onfbxd {
  d: path("M2.5 16.5a9.5 9.5 0 0 1 19 0m-19 0h19");
}

.xlrgsobgu {
  d: path("m12 16.5l3.5-6");
}

.yj2kwourk {
  fill: currentColor;
  d: path("m19.207 8.982l1.061 1.061l-2.652 2.652l-1.061-1.061Z");
}

</style>
