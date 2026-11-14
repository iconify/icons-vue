<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c10dxy0af"/><path class="kuosxwh9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-tow-bar" /></template>
<style>
.c10dxy0af {
  d: path("M2.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5 0h4m6-5.75H13a1.5 1.5 0 0 0-1.5 1.5v8.5a1.5 1.5 0 0 0 1.5 1.5h4.5");
}

.kuosxwh9l {
  d: path("M14.5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
