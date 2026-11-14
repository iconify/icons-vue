<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl_x84b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heritage-trail" /></template>
<style>
.xl_x84b7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C5 14 9 10.5 12 10.5s7 3.5 9.5 10m-9.5-10V3m0 0l5 1.75l-5 1.75Zm2 15.5h.01m-4.01-2h.01M13 14h.01");
}

</style>
