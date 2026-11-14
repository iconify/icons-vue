<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0istc4pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conical-flask" /></template>
<style>
.r0istc4pl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v6.25l-5.25 9.5C4.25 19.9 4.9 21 6.2 21h11.6c1.3 0 1.95-1.1 1.45-2.25L14 9.25V3M9 3h6M7.75 15.5h8.5");
}

</style>
