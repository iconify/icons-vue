<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on_qifbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-network" /></template>
<style>
.on_qifbjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-14 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM6.75 6.75l3 3m4.5 4.5l3 3m0-10.5l-3 3m-4.5 4.5l-3 3");
}

</style>
