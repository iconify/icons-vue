<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ats88qb5k"/><path class="s-q4tibsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-trip" /></template>
<style>
.ats88qb5k {
  d: path("M6 7h12v12.5H6Zm3.5 0V2.5h5V7");
}

.s-q4tibsy {
  d: path("M8 20.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm6 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
