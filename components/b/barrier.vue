<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8gs6cm6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barrier" /></template>
<style>
.i8gs6cm6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h17a1 1 0 0 1 1 1v5H4a1 1 0 0 1-1-1zm2 6v5m14-5v5M3 18h4m10 0h4M3 7l6 6m0-6l6 6m0-6l6 6");
}

</style>
