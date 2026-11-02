<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv6re7bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line" /></template>
<style>
.mv6re7bek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 16l4-4a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 0 2 0l8-8M3 4v14a2 2 0 0 0 2 2h16");
}

</style>
