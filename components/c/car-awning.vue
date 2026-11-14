<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k9qa0gl6r"/><path class="imh72tbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-awning" /></template>
<style>
.imh72tbms {
  d: path("M3.5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.75 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14 6.5l7.5 12");
}

.k9qa0gl6r {
  d: path("M2.5 14.5v-3q0-1 1-1H6l2.5-4H14v8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
