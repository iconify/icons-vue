<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jkd09vhat"/><path class="u2jau1bso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-warm" /></template>
<style>
.jkd09vhat {
  d: path("M14.072 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.68 0 3.203.351 4.431.977M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11.25 10.5v-5a1.5 1.5 0 0 1 3 0v5");
}

.u2jau1bso {
  fill: currentColor;
  d: path("M16.75 19.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
