<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2aye46cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gym-cleaning" /></template>
<style>
.x2aye46cp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h9v10.5H4Zm2 0V5a1.5 1.5 0 0 1 1.5-1.5h7V7h-4v4m.75-4l1.25 2M18 3.5h.01m2.49 2.25h.01M18 8h.01");
}

</style>
