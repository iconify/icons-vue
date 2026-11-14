<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ln07machm"/><path class="clmrij5rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:granite-rock" /></template>
<style>
.clmrij5rf {
  d: path("m10.5 3.5l2.5 6l8.5 2M7 12.5h.01M11.5 16h.01m4.99-1h.01");
}

.ln07machm {
  d: path("M2.5 15L5 7.5l5.5-4l7 1.5l4 6.5l-2 8l-8.5 1L4 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
