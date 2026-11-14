<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jazp-sb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-snap" /></template>
<style>
.jazp-sb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13V5.5a3 3 0 0 1 6 0V13a5 5 0 1 1-6 0ZM18.5 3v17.5M16 18l2.5 2.5L21 18M8 13.5V17");
}

</style>
