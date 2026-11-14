<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wm8dsn4pf"/><path class="cfnyd4lto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-hiss" /></template>
<style>
.cfnyd4lto {
  d: path("M8.5 14h7c0 2.25-1.5 3.5-3.5 3.5S8.5 16.25 8.5 14Zm-1-4l2.5 1m6.5-1L14 11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wm8dsn4pf {
  d: path("M5 9L3 5.5l4.5.5c1.5-1 7.5-1 9 0l4.5-.5L19 9c1 2 1 4 .5 6c-1 3.5-4 5.5-7.5 5.5s-6.5-2-7.5-5.5C4 13 4 11 5 9Z");
}

</style>
