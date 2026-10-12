<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct27f56nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cross-dock-sharp" /></template>
<style>
.ct27f56nv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75h6.5v18.5h-6.5zM2.75 8h4M5 5.75L7.25 8L5 10.25M16.75 16h4.5M19 13.75L21.25 16L19 18.25");
}

</style>
