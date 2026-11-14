<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j046bzbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-quick-replies" /></template>
<style>
.j046bzbrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H8L5 12V9.5h-.5a2 2 0 0 1-2-2Zm7 8.25h12v3h-12Zm0 6h12v3h-12Z");
}

</style>
