<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="a1k57lb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charging-station-event" /></template>
<style>
.a1k57lb9v {
  d: path("m13 6l-4.5 6.5h3.25L11 18l4.5-6.5h-3.25Z");
}

.f18_f1p2j {
  d: path("M5.5 2.5h13v19h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
