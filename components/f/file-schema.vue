<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g545owb_j"/><path class="fb50f0b5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-schema" /></template>
<style>
.fb50f0b5b {
  d: path("M15.5 2.5V5A1.5 1.5 0 0 0 17 6.5h2.5M7.5 7h4v4h-4Zm5 7.5h4v4h-4Zm-3-3.5v5.5h3");
}

.g545owb_j {
  d: path("M7 2.5h8.5l4 4V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
