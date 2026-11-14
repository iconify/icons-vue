<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l07xlrb8y"/><path class="dil1r7baf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:device-charging-error" /></template>
<style>
.dil1r7baf {
  d: path("M11.5 6L8 12h4l-2.5 5m8.5-2.5V18m0 3h.01");
}

.l07xlrb8y {
  d: path("M15.2 21H4.5V2.5H16v9.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
