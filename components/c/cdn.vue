<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sn-2akbwq"/><path class="l-yb2vvhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cdn" /></template>
<style>
.l-yb2vvhy {
  d: path("M9.5 12a2.5 6.25 0 1 0 5 0a2.5 6.25 0 1 0-5 0Zm-7-9.5h3v3h-3Zm16 0h3v3h-3Zm-16 16h3v3h-3Zm16 0h3v3h-3Z");
}

.sn-2akbwq {
  d: path("M5.75 12a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
