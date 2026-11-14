<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hma0ejb7z"/><path class="z_h4iyytk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loveseat" /></template>
<style>
.hma0ejb7z {
  d: path("M4.5 10V8.5A2.5 2.5 0 0 1 7 6h10a2.5 2.5 0 0 1 2.5 2.5V10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_h4iyytk {
  d: path("M2.5 12a2 2 0 0 1 4 0v2h11v-2a2 2 0 0 1 4 0v6h-19ZM12 6v12");
}

</style>
