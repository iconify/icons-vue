<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbqwyt1yv"/><path class="x-ss8bldv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:continue-watching" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbqwyt1yv {
  d: path("M2.5 3h19v12.5h-19Z");
}

.x-ss8bldv {
  d: path("m10 6l5 3.25l-5 3.25ZM2.5 20H13m0 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0h5.5");
}

</style>
