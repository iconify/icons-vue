<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgrv0-bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:amputee-football" /></template>
<style>
.bgrv0-bha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a9 9 0 0 1 11-11a9 9 0 0 1-11 11Zm13-15H21m-4.75 0l2 11m2-11l-2 11v8m-12.75-7l5-5m-4.75 2.75l2 2m.5-4.5l2 2m7-3.25h2");
}

</style>
