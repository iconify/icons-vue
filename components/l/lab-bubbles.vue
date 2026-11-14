<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vkvq8fyeh"/><path class="cjuzsohos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-bubbles" /></template>
<style>
.cjuzsohos {
  d: path("M8.25 16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4.25-5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM11 6h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkvq8fyeh {
  d: path("M4 3h1.5v15.5A2.5 2.5 0 0 0 8 21h8a2.5 2.5 0 0 0 2.5-2.5V3");
}

</style>
