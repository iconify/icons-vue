<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zrjqjgbgu"/><path class="g_godccaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:burnup-chart" /></template>
<style>
.g_godccaa {
  d: path("m7 17l4.5-4l3.5-2l4-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrjqjgbgu {
  d: path("M3.5 3.5v17h17M7 6.5h13.5");
}

</style>
