<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="twazkm86z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disk-volume" /></template>
<style>
.oeucrxbku {
  d: path("M3.5 2.5h17v19h-17Z");
}

.twazkm86z {
  d: path("M6.5 10.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm5.5 0h.01M7 18.75h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
