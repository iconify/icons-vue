<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="czynfpb5e"/><path class="c5ayajb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-swift-code" /></template>
<style>
.c5ayajb3g {
  d: path("M15 8.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm2.25-1c1.25-3 4.25-4.5 4-2.5c-.25 1.5-2 2.25-4 2.5M7.5 13l3.25-2.5L14 13Zm1.25 0v3.25m4-3.25v3.25m-5.25 0H14");
}

.czynfpb5e {
  d: path("m12.354 5.075l6.717.354l.354 6.717l-9.193 9.193l-7.071-7.071Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
