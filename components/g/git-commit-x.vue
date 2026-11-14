<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbc3wi5yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-commit-x" /></template>
<style>
.rbc3wi5yj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h4m0 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 0h7M15 15l6 6m0-6l-6 6");
}

</style>
