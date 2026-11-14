<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gdku3cb8n"/><path class="czfodcbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liver" /></template>
<style>
.czfodcbju {
  d: path("M13.5 5q0 4.5-3 7.5");
}

.gdku3cb8n {
  d: path("M3 8c0-2 1.5-3 3.5-3H19c1.5 0 2.5 1.5 1.75 3C19 11.5 15.5 15.5 11 17.5c-2.5 1-5.5 1-7-1c-.75-1.5-1-5-1-8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
