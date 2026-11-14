<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gizug3b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-security-wifi" /></template>
<style>
.gizug3b6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4L17 7.25l-1.25 5.25l-13.5-3.25Zm2.75 6.25v5.25H3M3 13v5m13.5 1.25a2.5 2.5 0 0 1 3.5 0m-5.5-2a5.3 5.3 0 0 1 7.5 0");
}

</style>
