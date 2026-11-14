<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkhbhcb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:control-arm" /></template>
<style>
.mkhbhcb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm15-6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-13-4.5v9m1.75 1.25l11.5-5m-11.5-6.5l11.5 5");
}

</style>
