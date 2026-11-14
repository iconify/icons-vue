<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cacr6e5sv"/><path class="w2kfng41j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:belt-drive" /></template>
<style>
.cacr6e5sv {
  d: path("m9.75 6.5l6.75 2a3.75 3.75 0 1 1 0 7l-6.75 2a5.75 5.75 0 1 1 0-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w2kfng41j {
  d: path("M5.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12.25 0h.01");
}

</style>
