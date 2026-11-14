<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="h9wjmwbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:color-wheel" /></template>
<style>
.h9wjmwbsr {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-9.5V9m8.227-1.75l-5.629 3.25m5.629 6.25l-5.629-3.25M12 21.5V15m-8.227 1.75l5.629-3.25M3.773 7.25l5.629 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
