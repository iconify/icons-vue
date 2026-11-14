<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q84wighcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fracking" /></template>
<style>
.q84wighcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 16.5l3.25-14h2.5l3.25 14m-12 0h15M9.25 9l6.5 4.5m-1-4.5l-6.5 4.5m2 3V19L12 21.5l1.75-2.5v-2.5");
}

</style>
