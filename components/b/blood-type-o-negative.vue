<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m877e7bkt"/><path class="ipn28vbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-type-o-negative" /></template>
<style>
.ipn28vbme {
  fill: currentColor;
  d: path("M15 19h6c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19Z");
}

.m877e7bkt {
  d: path("M2.75 9.25a5.75 6.75 0 1 0 11.5 0a5.75 6.75 0 1 0-11.5 0ZM16.5 4.5h4M18 14c1.75 2 3 3.5 3 5c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19c0-1.5 1.25-3 3-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
