<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e355kti5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:erlenmeyer-sharp" /></template>
<style>
.e355kti5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 7.5h2.5v3.91a5 5 0 1 1-2.5 0ZM10 2.75h4v2.5h-4zM9 15h6");
}

</style>
