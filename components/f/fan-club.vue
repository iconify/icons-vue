<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="czyvlv4fd"/><path class="l4h51cbye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fan-club" /></template>
<style>
.czyvlv4fd {
  d: path("M4 2.5v19m0-19L20.5 9L4 15.5Z");
}

.l4h51cbye {
  d: path("m9.25 6.5l.588 1.691l1.79.036l-1.427 1.082l.518 1.714L9.25 10l-1.469 1.023l.518-1.714l-1.427-1.082l1.79-.036Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
