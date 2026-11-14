<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f04pnvbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lectern-podium" /></template>
<style>
.f04pnvbkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.521 9.078l15.034-4.177A1.14 1.14 0 0 1 21 6v.378a1.5 1.5 0 0 1-1.077 1.439L5.389 12.092a1.5 1.5 0 0 1-1.847-.965l-.043-.13a1.5 1.5 0 0 1 1.022-1.919M10.5 10.75V20m3-10.25V20m-8 0h13");
}

</style>
