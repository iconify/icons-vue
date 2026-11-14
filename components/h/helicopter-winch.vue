<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8sctbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helicopter-winch" /></template>
<style>
.tj8sctbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h13M9 3v3.5m5.5 7.5h-8a3 3 0 0 1-3-3A4.5 4.5 0 0 1 8 6.5h4.5a2 2 0 0 1 2 2zm0-4.5h6l.75-3M9 14v5a1.75 1.75 0 0 1-3.5 0");
}

</style>
