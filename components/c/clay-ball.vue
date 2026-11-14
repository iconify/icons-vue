<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="brpi5xbgf"/><path class="y60ga1b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clay-ball" /></template>
<style>
.brpi5xbgf {
  d: path("M15.25 3.25a9.5 9.5 0 1 0 6 7a6 6 0 0 1-6-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y60ga1b0n {
  d: path("M16 11.5a9 9 0 0 1-3.5-5");
}

</style>
