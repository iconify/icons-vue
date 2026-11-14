<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2a2_ab6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blessing-hands" /></template>
<style>
.z2a2_ab6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21V10.75a2.25 2.25 0 0 0-4.5 0v5L4.25 14a1.25 1.25 0 0 0-1.75 1.75l4 5.25m7 0V10.75a2.25 2.25 0 0 1 4.5 0v5L19.75 14a1.25 1.25 0 0 1 1.75 1.75l-4 5.25M12 2.5v4M5.75 3l1.5 2.5m11-2.5l-1.5 2.5");
}

</style>
