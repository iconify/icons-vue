<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb9-s99qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-pyramid" /></template>
<style>
.qb9-s99qs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.955 17.896l6.517-11.662a1.75 1.75 0 0 1 3.056 0l6.517 11.662a1.75 1.75 0 0 1-1.528 2.604H5.483a1.75 1.75 0 0 1-1.528-2.604M8.75 9.25h6.5M5.5 15h13M12 17.75h.01");
}

</style>
