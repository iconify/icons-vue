<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c0hayn6xe"/><path class="lozyymb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hourglass-half" /></template>
<style>
.c0hayn6xe {
  d: path("M7 3h10v2.5c0 2.5-2.5 5-5 6.5c2.5 1.5 5 4 5 6.5V21H7v-2.5c0-2.5 2.5-5 5-6.5c-2.5-1.5-5-4-5-6.5ZM5 3h14M5 21h14");
}

.lozyymb0f {
  d: path("M10 7h4c-.5 1.25-1.25 2-2 2.5c-.75-.5-1.5-1.25-2-2.5Zm0 11h4c-.25-1-1-1.75-2-2c-1 .25-1.75 1-2 2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
