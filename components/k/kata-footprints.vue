<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqecggamp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kata-footprints" /></template>
<style>
.uqecggamp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 18a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0Zm6.5-6a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0Zm6.5-6a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0Z");
}

</style>
