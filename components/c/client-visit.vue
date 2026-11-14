<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4gsxbbiy"/><path class="w1wcgmkkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:client-visit" /></template>
<style>
.r4gsxbbiy {
  d: path("M13.5 16.9v4.6H3v-19h10.5v14.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1wcgmkkl {
  d: path("M6.5 21.5V17H10v4.5M6.5 7h.01M10 7h.01M6.5 11.5h.01m3.49 0h.01m8.99 10c-1.5-1.5-2.75-3-2.75-4.75a2.75 2.75 0 0 1 5.5 0c0 1.75-1.25 3.25-2.75 4.75Z");
}

</style>
