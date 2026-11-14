<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bn5xnybil"/><path class="zo_drspwk"/><path class="aufr3tbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:action-marketplace" /></template>
<style>
.aufr3tbrr {
  d: path("M8 20.5V15h4v2.6m6.75-4.1L15 18.25h3L16.75 22L21 16.75h-3Z");
}

.bn5xnybil {
  d: path("m3.5 8l2-4.5h13l2 4.5a2.125 2.125 0 0 1-4.25 0A2.125 2.125 0 0 1 12 8a2.125 2.125 0 0 1-4.25 0A2.125 2.125 0 0 1 3.5 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zo_drspwk {
  d: path("M5 10v10.5h4.7m9.3-7.6V10");
}

</style>
