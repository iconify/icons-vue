<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u607g3bse"/><path class="l3c0z21cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-instant-access" /></template>
<style>
.l3c0z21cg {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m5.25 5.75L15.5 18.5H18l-.75 3.25l3.25-4.25H18Z");
}

.u607g3bse {
  d: path("M12.371 17.999L12 18c-.75 0-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q-.002 1.041-.349 1.931");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
