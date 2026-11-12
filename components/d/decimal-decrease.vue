<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id9fyhbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:decimal-decrease" /></template>
<style>
.id9fyhbnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 5a2 2 0 1 1 4 0v2a2 2 0 1 1-4 0ZM7 9h.01M6 15l-3 3l3 3m-3-3h18");
}

</style>
