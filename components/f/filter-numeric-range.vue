<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl-gw0buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:filter-numeric-range" /></template>
<style>
.bl-gw0buw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.464 19.232L8 17.5V11L2.5 3.5h15L12 11v2.999m2.25 2.751h7.5v3.75h-7.5Zm2 0v1.5m1.75-1.5v2m1.75-2v1.5");
}

</style>
