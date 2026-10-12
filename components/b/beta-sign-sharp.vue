<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9fb2ybmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beta-sign-sharp" /></template>
<style>
.i9fb2ybmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.5a4.75 4.75 0 0 1 9.5 0c0 2-1.5 3.5-3.5 3.5c2.75 0 4.75 1.75 4.75 4.25s-2 4.25-4.75 4.25c-2.25 0-4.25-1.25-6-3m0-9V21");
}

</style>
