<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-o_r1b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bubble" /></template>
<style>
.g-o_r1b9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M3 4v14a2 2 0 0 0 2 2h16");
}

</style>
