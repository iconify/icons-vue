<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kouyg8b6l"/><path class="assub4bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fish-farm" /></template>
<style>
.assub4bfz {
  d: path("M6.25 12c2.5-3.75 7.25-3.75 9 0l2.5-2.25v4.5L15.25 12c-1.75 3.75-6.5 3.75-9 0Zm3.5-.25h.01");
}

.kouyg8b6l {
  d: path("M3.5 3.5h17v17h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
