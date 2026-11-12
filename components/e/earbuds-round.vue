<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7yx_n5xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:earbuds-round" /></template>
<style>
.v7yx_n5xe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4c2 0 4 1 4 3v13c0 1-2 1-2 0V10H6q-3 0-3-3t3-3m12 0c-2 0-4 1-4 3v13c0 1 2 1 2 0V10h2q3 0 3-3t-3-3M6 7h.01M18 7h.01");
}

</style>
