<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lfig8ybxr"/><path class="ua7vdh5wt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:couple-hug" /></template>
<style>
.lfig8ybxr {
  d: path("M5.25 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm8 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM2.5 21.5c0-6.5 2.5-10 5.5-10c2 0 3.25 1 4 2c.75-1 2-2 4-2c3 0 5.5 3.5 5.5 10");
}

.ua7vdh5wt {
  d: path("M5 16.5q7 3 14 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
