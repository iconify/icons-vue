<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1mm6i9gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guppy" /></template>
<style>
.z1mm6i9gw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12c0-3.5 3-5 6-5s4.5 2.5 5 5c-.5 2.5-2 5-5 5s-6-1.5-6-5Zm11 0l6.5-6.5c1.5 3 1.5 10 0 13Zm-7.5-1h.01");
}

</style>
