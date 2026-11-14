<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngxwksboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curling-brush" /></template>
<style>
.ngxwksboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.718 4.282l-8.839 8.839M8.757 11L13 15.243a2 2 0 0 1 0 2.828a2 2 0 0 1-2.828 0l-4.243-4.243a2 2 0 0 1 0-2.828a2 2 0 0 1 2.828 0");
}

</style>
