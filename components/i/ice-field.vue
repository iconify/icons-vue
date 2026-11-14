<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nsw3vd67i"/><path class="feb8ak-4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-field" /></template>
<style>
.feb8ak-4p {
  d: path("m9 19.5l2-2.75l-1-1.25l2.25-2.5M15 3.75q0 2.75 2.75 2.75Q15 6.5 15 9.25q0-2.75-2.75-2.75Q15 6.5 15 3.75ZM6.5 7.5h.01");
}

.nsw3vd67i {
  d: path("M3 19.5L7.5 13H21l-4.5 6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
