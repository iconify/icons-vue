<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9t0l12ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-pack" /></template>
<style>
.k9t0l12ji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h17v11h-17Zm17 3.5h2v4h-2M7.5 9V6.5a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2V9m-8 3v5m3-5v5m3-5v5");
}

</style>
