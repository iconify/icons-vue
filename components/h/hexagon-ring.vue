<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbzvr-3ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hexagon-ring" /></template>
<style>
.pbzvr-3ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 12l4.75-8.25m0 0h9.5m0 0L21.5 12m0 0l-4.75 8.25m0 0h-9.5m0 0L2.5 12");
}

</style>
