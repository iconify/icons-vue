<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ligps7bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:couple-two-men" /></template>
<style>
.ligps7bcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-2 11.5c0-3.25 2.25-5 5-5s4.5 1.75 4.5 5M13.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM12 19.5c0-3.25 1.75-5 4.5-5s5 1.75 5 5");
}

</style>
