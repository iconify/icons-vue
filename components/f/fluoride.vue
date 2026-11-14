<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk3g15frq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fluoride" /></template>
<style>
.gk3g15frq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.676 16.754l.574-3.254c.5-2 1.75-4 1.75-6.5c0-2.75-1.25-4.5-3.5-4.5c-1.25 0-1.75.75-2.75.75S7.25 2.5 6 2.5C3.75 2.5 2.5 4.25 2.5 7c0 2.5 1.25 4.5 1.75 6.5L5 17.75c.25 1.5 2 1.5 2.25 0L8 14.5c.25-1 1.25-1 1.5 0l.75 3.25c.204 1.222 1.404 1.449 1.976.679m6.024-4.679c1.5 1.5 3.25 3.25 3.25 5a3.25 3.25 0 0 1-6.5 0c0-1.75 1.75-3.5 3.25-5Z");
}

</style>
