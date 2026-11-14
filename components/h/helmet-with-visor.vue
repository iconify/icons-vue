<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb9w1yb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helmet-with-visor" /></template>
<style>
.hb9w1yb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11.5a7.5 7.5 0 0 1 15 0m-16 0h19m-8.5 0V17a2.5 2.5 0 0 0 2.5 2.5H19a2.5 2.5 0 0 0 2.5-2.5v-5.5");
}

</style>
