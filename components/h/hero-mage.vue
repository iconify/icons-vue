<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mb42mob8y"/><path class="vq-g13gbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hero-mage" /></template>
<style>
.mb42mob8y {
  d: path("M2.5 18a9.5 2.75 0 1 0 19 0a9.5 2.75 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vq-g13gbe {
  d: path("m7.5 15.5l5-8.5l4 8.5m-4-13q.5 1.75 2.25 2.25Q13 5.25 12.5 7q-.5-1.75-2.25-2.25Q12 4.25 12.5 2.5Z");
}

</style>
