<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmspe5zyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-guidance" /></template>
<style>
.nmspe5zyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V3M9.25 5.75L12 3l2.75 2.75M12 17l-7-7m3.5 0H5v3.5m7 3.5l7-7m-3.5 0H19v3.5");
}

</style>
