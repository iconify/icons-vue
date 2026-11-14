<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="atlkmy-qz"/><path class="cfd5cmuur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fallopian-tubes" /></template>
<style>
.atlkmy-qz {
  d: path("M8.5 9c0-1 1-1.5 3.5-1.5s3.5.5 3.5 1.5c0 3.5-1.5 6-2.25 7.5v4h-2.5v-4C10 15 8.5 12.5 8.5 9Z");
}

.cfd5cmuur {
  fill: currentColor;
  d: path("M8.5 8.5c-2-3-5.5-3.5-6 0c-.25 1.75.75 3 2 3v-2c1-1 2.5-.5 4 1Zm7 0c2-3 5.5-3.5 6 0c.25 1.75-.75 3-2 3v-2c-1-1-2.5-.5-4 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
