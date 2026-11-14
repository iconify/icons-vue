<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd91p9bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drive-shaft" /></template>
<style>
.sd91p9bku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h2v8h-2Zm2 1.5h2a2.5 2.5 0 0 1 0 5h-2M9 12h6m4.5-2.5h-2a2.5 2.5 0 0 0 0 5h2m0-6.5h2v8h-2Z");
}

</style>
