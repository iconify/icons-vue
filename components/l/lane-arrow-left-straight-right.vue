<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o96wbz42y"/><path class="z_302zbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-arrow-left-straight-right" /></template>
<style>
.o96wbz42y {
  d: path("M12 21V3.5M8.5 7L12 3.5L15.5 7M12 17a5 5 0 0 0-5-5H3.5m8.5 5a5 5 0 0 1 5-5h3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_302zbkl {
  d: path("m6.5 9l-3 3l3 3m11-6l3 3l-3 3");
}

</style>
