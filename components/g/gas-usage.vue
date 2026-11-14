<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z2wt-_fvk"/><path class="pnqn2d98s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-usage" /></template>
<style>
.pnqn2d98s {
  d: path("M6.25 13a4.75 4.75 0 0 1 9.5 0M11 13l2.75-3.5m4.75 4.25c.75 2 3 3 3 5.25a3 3 0 0 1-6 0c0-1.25.5-2 1.25-2.75c.25 1 .75 1.5 1.25 1.5c0-1.5-.25-2.75.5-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2wt-_fvk {
  d: path("M12.7 18.5H2.5v-16h17v6");
}

</style>
