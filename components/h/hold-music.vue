<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n6nyoxd0n"/><path class="jv817f4kp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hold-music" /></template>
<style>
.jv817f4kp {
  d: path("M14 9a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 14 9Z");
}

.n6nyoxd0n {
  d: path("M8.5 3.5c.8 0 1.3.5 1.5 1.25l.75 3c.15.75-.15 1.35-.75 1.75l-1.5 1c1.2 2.5 2.4 3.8 5 5l1-1.5c.4-.6 1-.9 1.75-.75l3 .75c.75.2 1.25.7 1.25 1.5v3c0 1.1-.9 2-2 2c-8 0-15-7-15-15c0-1.1.9-2 2-2Zm9 5.5V2.75m0 0l3 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
