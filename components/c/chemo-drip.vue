<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vag0rmbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chemo-drip" /></template>
<style>
.vag0rmbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10V10c0 2-2 3.5-5 4.5c-3-1-5-2.5-5-4.5Zm5 11V17m-2 0h4v4.5h-4Zm2-8.5h.01");
}

</style>
