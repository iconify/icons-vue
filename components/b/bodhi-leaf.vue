<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y19ic75yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bodhi-leaf" /></template>
<style>
.y19ic75yo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17c-2 1.5-8 1.5-8-4c0-4.5 5-7 8-10.5c3 3.5 8 6 8 10.5c0 5.5-6 5.5-8 4Zm0 4.5v-14");
}

</style>
