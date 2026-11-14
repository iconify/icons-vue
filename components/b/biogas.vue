<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vidj6tfxk"/><path class="be85ku2dt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biogas" /></template>
<style>
.be85ku2dt {
  d: path("M18.5 10c.5-3 1.5-4.5 3-5c.25 2.5-1 4.5-3 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vidj6tfxk {
  d: path("M3 19.5V11a5.5 5.5 0 0 1 11 0v8.5Zm11-6h4.5V10m0 0c-2.5-.5-3.5-3-3-5.5C18 5 19 7 18.5 10Z");
}

</style>
