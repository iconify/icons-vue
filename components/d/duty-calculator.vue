<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c-fiunb8n"/><path class="mt8y93eyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duty-calculator" /></template>
<style>
.c-fiunb8n {
  d: path("M5 3.5h14v17H5Z");
}

.mt8y93eyj {
  d: path("M8 6.5h8V10H8ZM9 13h.01M12 13h.01M15 13h.01M9 16.5h.01m2.99 0h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
