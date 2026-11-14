<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tp-0vzbpb"/><path class="k-9dpk9hv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifting-sling" /></template>
<style>
.k-9dpk9hv {
  d: path("m7 14l5-5.5l5 5.5M3.5 14h17v7.5h-17Z");
}

.tp-0vzbpb {
  d: path("M14 2.5v4a2 2 0 0 1-4 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
