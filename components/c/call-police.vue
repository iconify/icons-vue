<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luduox4od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-police" /></template>
<style>
.luduox4od {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5H6l1 3l-1.5 1c.75 1.5 2.25 3 3.75 3.75l1.25-1.5l3 1v2a1.75 1.75 0 0 1-1.75 1.75c-5.25 0-9.25-4-9.25-9.25A1.75 1.75 0 0 1 4.25 2.5ZM18.5 15l3 1v2c0 1.75-1.25 3-3 3.75c-1.75-.75-3-2-3-3.75v-2Z");
}

</style>
