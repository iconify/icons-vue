<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jjj7wfbku"/><path class="yu-ueubcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-breed-siamese" /></template>
<style>
.jjj7wfbku {
  d: path("m4 3l5 3.5h6L20 3v8c0 5.5-3.5 10-8 10s-8-4.5-8-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yu-ueubcw {
  d: path("M9.5 13.75h5L12 17.5ZM8.5 11h.01m6.99 0h.01");
}

</style>
