<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uldzsundl"/><path class="fcsl4vbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-parking-permit" /></template>
<style>
.fcsl4vbyw {
  d: path("M10 15V6.5h2.5a2.5 2.5 0 0 1 0 5H10m.5 7.5h3");
}

.uldzsundl {
  d: path("M5.5 2h13v20h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
