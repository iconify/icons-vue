<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xloj4vbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:class-action" /></template>
<style>
.xloj4vbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM7.5 20c0-3.25 2-5.25 4.5-5.25s4.5 2 4.5 5.25M2.75 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm14.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 20c0-3 1-5 2.5-5.5M21.5 20c0-3-1-5-2.5-5.5");
}

</style>
