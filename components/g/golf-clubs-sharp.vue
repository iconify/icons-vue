<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="le2xg4a0g"/><circle class="fnb_mpb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:golf-clubs-sharp" /></template>
<style>
.fnb_mpb7x {
  cx: 16.5px;
  cy: 17.75px;
  r: 3px;
}

.le2xg4a0g {
  d: path("M7.25 20.75v-11m.94-6.15l7.62 2.8l.94.35l-.94.35l-7.62 2.8l-.94.35v-7zM3.75 20.75h7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
