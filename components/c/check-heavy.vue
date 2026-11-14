<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuq4usk9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:check-heavy" /></template>
<style>
.cuq4usk9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.061 11.439l.878-.878a1.5 1.5 0 0 1 2.122 0l1.378 1.378a1.5 1.5 0 0 0 2.122 0l6.378-6.378a1.5 1.5 0 0 1 2.122 0l.878.878a1.5 1.5 0 0 1 0 2.122l-9.378 9.378a1.5 1.5 0 0 1-2.122 0l-4.378-4.378a1.5 1.5 0 0 1 0-2.122");
}

</style>
