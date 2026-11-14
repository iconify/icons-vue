<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6yrobgal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forceps" /></template>
<style>
.w6yrobgal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 3.5c0-1 3-1 3 0m-3 0l-3.75 13c-.25 1.25.75 3 3 4.75M13.5 3.5l3.75 13c.25 1.25-.75 3-3 4.75m-6-10.75l1.5.5m6-.5l-1.5.5");
}

</style>
