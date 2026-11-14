<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avs0_zbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-silhouette-female" /></template>
<style>
.avs0_zbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-.75 4.5h5l-1 3.25l3.5 5H7l3.5-5Zm0 0l-3 4.5m8-4.5l3 4.5m-7 3.75v4.5m3-4.5v4.5");
}

</style>
