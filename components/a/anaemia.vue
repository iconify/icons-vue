<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1v9ipo8j"/><path class="n-s9bybax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anaemia" /></template>
<style>
.f1v9ipo8j {
  d: path("M12 2.25C15.75 7 19.25 10.5 19.25 14.5s-3.25 7-7.25 7s-7.25-3-7.25-7S8.25 7 12 2.25Z");
}

.n-s9bybax {
  fill: currentColor;
  d: path("M5.25 16.5h13.5c-.5 3-3.25 5-6.75 5s-6.25-2-6.75-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
