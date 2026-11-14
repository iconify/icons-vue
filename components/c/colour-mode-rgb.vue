<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zo8kfr3hy"/><path class="gjo4n6j4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-mode-rgb" /></template>
<style>
.gjo4n6j4d {
  d: path("M4.75 9h3v3h-3Zm5.75 0h3v3h-3Zm5.75 0h3v3h-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zo8kfr3hy {
  d: path("M2 4h20v13H2Zm10 13v3.5m-4 0h8");
}

</style>
