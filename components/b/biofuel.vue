<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6n6noo0n"/><path class="qneyrr7wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biofuel" /></template>
<style>
.l6n6noo0n {
  d: path("M12 2.5s7 7.5 7 12a7 7 0 0 1-14 0c0-4.5 7-12 7-12Z");
}

.qneyrr7wx {
  d: path("M9 17.5q0-6 6-6q0 6-6 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
