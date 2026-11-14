<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="owhfljerj"/><path class="axnesfb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:disclosure-form" /></template>
<style>
.axnesfb5m {
  d: path("M7.5 6H10v2.5H7.5Zm5 1.25h4M7.5 11H10v2.5H7.5Zm5 1.25h1.9M7.5 16.5H11m3 1.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4-2.25h.01M18 18v2.25");
}

.owhfljerj {
  d: path("M12.2 21.5H4.5v-19h15v8.9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
