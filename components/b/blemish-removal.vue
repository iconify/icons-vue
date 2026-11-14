<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jr-gnybef"/><path class="f4iiuef-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blemish-removal" /></template>
<style>
.f4iiuef-p {
  d: path("M13.5 8.25a2.75 2.75 0 0 1 2.382 1.375m0 2.75A2.75 2.75 0 0 1 13.5 13.75m-2.382-1.375a2.75 2.75 0 0 1 0-2.75");
}

.jr-gnybef {
  d: path("M7 21.5v-4c-2.5-1.5-3.5-4-3.5-7c0-4.5 3.5-8 8.5-8c4 0 6.5 2.5 7 6l1.5 3H19V14c0 1.5-1 2.5-2.5 2.5H15v5M13.5 11h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
