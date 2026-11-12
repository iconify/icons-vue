<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ki81b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-sparkline-sharp" /></template>
<style>
.q2ki81b8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 18l4-4l4 3l5-9m0-4a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4");
}

</style>
