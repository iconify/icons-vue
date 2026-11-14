<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l0d_e2z8q"/><path class="h8rhonb3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ally-marker" /></template>
<style>
.h8rhonb3c {
  d: path("M10 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9.5 15c0-1.5 1-2.5 2.5-2.5s2.5 1 2.5 2.5");
}

.l0d_e2z8q {
  d: path("M12 21.5c-3-2.75-7.25-7-7.25-11.75a7.25 7.25 0 0 1 14.5 0c0 4.75-4.25 9-7.25 11.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
