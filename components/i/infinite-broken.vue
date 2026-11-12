<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yygr_ccfm"/><path class="ntftecckr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:infinite-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntftecckr {
  d: path("M7 17C9.76142 17 10.5 15 12 12C13.5 9 14.2386 7 17 7");
}

.yygr_ccfm {
  d: path("M10.0005 8C9.16474 7.37209 8.12582 7 7 7C4.23858 7 2 9.23858 2 12C2 13.6356 2.78534 15.0878 3.99951 16M14 16C14.8357 16.6278 15.8743 17 17 17C19.7614 17 22 14.7614 22 12C22 10.3644 21.2147 8.91223 20.0005 8");
}

</style>
