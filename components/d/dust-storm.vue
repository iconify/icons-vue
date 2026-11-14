<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrb5n9bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dust-storm" /></template>
<style>
.nrb5n9bvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5H14a3 3 0 1 0-3-3m-8.5 7H12m3.5 0h.01m3.49 0h.01M6 16.5h10.5M9 20h.01M13 20h.01");
}

</style>
