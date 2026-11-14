<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zwcuk9brb"/><path class="f1uz493wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audiogram-chart" /></template>
<style>
.f1uz493wm {
  d: path("M17.5 16.75c0-.75.5-1.25 1.25-1.25s1 .75.75 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwcuk9brb {
  d: path("M3 3v17.5h10.2m-7.7-15L9 6.75l3 4L15 12M5.5 5.5h.01M9 6.75h.01m2.99 4h.01M16 16.5c0-1.5 1-2.5 2.5-2.5s2.5 1 2.5 2.5s-1.5 2-1.75 3c-.25 1.25-1 2-2 2c-.75 0-1.25-.5-1.25-1.25");
}

</style>
