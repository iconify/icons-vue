<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfa86ibrk"/><path class="r94bkc2jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-tracking-ai" /></template>
<style>
.qfa86ibrk {
  d: path("M11.182 15.499L11 15.5c-4 0-6.75-2-8.5-6c1.75-4 4.5-6 8.5-6s6.75 2 8.5 6q-.393.9-.855 1.664");
}

.r94bkc2jo {
  d: path("M8 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-1 0h8m-4-4v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
