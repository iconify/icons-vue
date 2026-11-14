<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anlvyqb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-braces" /></template>
<style>
.anlvyqb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 4h-.5a2 2 0 0 0-2 2v4a2 2 0 0 1-2 2a2 2 0 0 1 2 2v4a2 2 0 0 0 2 2H9m6-16h.5a2 2 0 0 1 2 2v4a2 2 0 0 0 2 2a2 2 0 0 0-2 2v4a2 2 0 0 1-2 2H15");
}

</style>
