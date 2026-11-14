<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="om3xhjljw"/><path class="u741y9bqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:engaged-couple" /></template>
<style>
.om3xhjljw {
  d: path("M6 15a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.u741y9bqd {
  d: path("M9.5 3h5L17 5.75L12 9L7 5.75ZM7 5.75h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
