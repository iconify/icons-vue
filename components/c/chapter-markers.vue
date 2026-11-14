<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrgu3sbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chapter-markers" /></template>
<style>
.lrgu3sbls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h14v19H3ZM17 5h3a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-3m0 3.5h3a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-3M6.5 7h7");
}

</style>
