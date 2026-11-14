<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v3b3hkdmg"/><path class="hi-wjtbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-ball-rack" /></template>
<style>
.hi-wjtbmu {
  d: path("M6 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-6 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3b3hkdmg {
  d: path("M3 3v18h18V3M3 12h18");
}

</style>
