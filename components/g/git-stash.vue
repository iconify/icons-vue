<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7yre729t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-stash" /></template>
<style>
.g7yre729t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 8v5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-5m-9-6v7m-3-3l3 3l3-3");
}

</style>
