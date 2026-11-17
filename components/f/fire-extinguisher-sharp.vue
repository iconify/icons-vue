<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmii5kbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fire-extinguisher-sharp" /></template>
<style>
.jmii5kbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a4 4 0 1 1 8 0v9H9zm4-4V5l6-2M9 15h8M13 5H9a4 4 0 0 0-4 4v7");
}

</style>
