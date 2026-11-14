<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk5-zdb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-share" /></template>
<style>
.tk5-zdb9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a2 2 0 0 1 2-2H9L12.5 6v13.5a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2ZM15 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3.5-5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.25-6.75l2-3m-2 5.5l2 3");
}

</style>
