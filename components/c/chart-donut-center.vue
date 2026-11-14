<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mhttnvbpw"/><path class="engkmybel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-donut-center" /></template>
<style>
.engkmybel {
  fill: currentColor;
  d: path("M9.5 11.25h5v1.5h-5Z");
}

.mhttnvbpw {
  d: path("M13.75 2.75A9.5 9.5 0 0 1 18 19.25l-2.25-2.75A6 6 0 0 0 13 6ZM15.25 21A9.5 9.5 0 0 1 3 15.25L6.25 14A6 6 0 0 0 14 17.75ZM2.5 12a9.5 9.5 0 0 1 7.75-9.25L11 6a6 6 0 0 0-5 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
