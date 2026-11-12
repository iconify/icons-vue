<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2k4kvwha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-union-duocolor-round" /></template>
<style>
.a2k4kvwha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h4a2 2 0 0 1 2 2v2a2 2 0 0 0 2 2h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2v-2a2 2 0 0 0-2-2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z");
}

</style>
