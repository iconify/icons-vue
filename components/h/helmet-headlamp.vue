<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t06moibgk"/><path class="r8xz9hbqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:helmet-headlamp" /></template>
<style>
.r8xz9hbqw {
  d: path("M14.5 10h3v3h-3Zm5.75-.5l1.5-1m-1.5 5l1.5 1");
}

.t06moibgk {
  d: path("M2.5 17.5V15a6.5 6.5 0 0 1 13 0v2.5m-13 0h16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
