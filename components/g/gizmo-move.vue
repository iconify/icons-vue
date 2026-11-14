<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_x6vib6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gizmo-move" /></template>
<style>
.z_x6vib6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 14V2.5M7.75 4.75L10 2.5l2.25 2.25M10 14h11m-2.5-2.5L21 14l-2.5 2.5M10 14l-6 6m0-3.5V20h3.5M13 8h2.75v2.75H13Z");
}

</style>
