<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmolz7rkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:factory-smoke" /></template>
<style>
.mmolz7rkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5V12l4.5-3v3L12 9v3h3.5V7.5h4v13ZM14.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4.25-.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM6 16h2m2.5 0h2");
}

</style>
