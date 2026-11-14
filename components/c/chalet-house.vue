<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rzh7fcbkh"/><path class="mdt0ajbdf"/><path class="ek02avbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chalet-house" /></template>
<style>
.ek02avbdz {
  d: path("M10 21v-4.5h4V21");
}

.mdt0ajbdf {
  d: path("M6 8.5V21h12V8.5");
}

.rzh7fcbkh {
  d: path("M2.5 12L12 2.5l9.5 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
