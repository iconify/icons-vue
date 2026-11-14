<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9dnuxbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:government-building-plus" /></template>
<style>
.j9dnuxbop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9a4.5 4.5 0 0 1 9 0M12 2.5v2M3 9h18M3 21h9.25M6 12v6m4-6v6m8-3v6m-3-3h6");
}

</style>
