<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxr3i4b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:committee" /></template>
<style>
.wxr3i4b7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6.5 20.5v-1c0-3 2.5-5.25 5.5-5.25s5.5 2.25 5.5 5.25v1M2.75 9.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 18c0-2.25 1.25-3.25 2.5-3.25m12.25-5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM21.5 18c0-2.25-1.25-3.25-2.5-3.25");
}

</style>
