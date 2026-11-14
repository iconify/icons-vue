<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n93pfsudu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drum-kit" /></template>
<style>
.n93pfsudu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0ZM4.102 4.474l6.761-1.812l.971 3.623l-6.762 1.811Zm10.648.776c1-2 5.5-2 6.5 0Zm3.25 0V18m-2 2.5l2-2.5l2 2.5");
}

</style>
