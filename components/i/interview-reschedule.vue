<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbw3ozz1z"/><path class="knpqv1ipd"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-reschedule" /></template>
<style>
.knpqv1ipd {
  d: path("M16.5 20.348A3 3 0 0 1 18 14.75");
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbw3ozz1z {
  d: path("M13.1 21H3.5V4.5h17v7.4M8 2.5v4m8-4v4m-12.5 3h17m-1 5.652A3 3 0 0 1 18 20.75");
}

</style>
