<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh36lya-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:folk-music-trio" /></template>
<style>
.rh36lya-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7 2.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm14.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM7.5 15.5c0-3.25 2-5.25 4.5-5.25s4.5 2 4.5 5.25M2 15.5c0-1.75 1.25-3.25 2.75-3.25c1.25 0 2.25.65 3 1.5m13.783-.033c-.497-.875-1.34-1.467-2.283-1.467c-1.25 0-2.25.65-3 1.5m-.25 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0V14.5c.5 1.5 2.25 1.5 2.25 3.25");
}

</style>
