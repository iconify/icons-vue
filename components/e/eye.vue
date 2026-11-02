<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfqcd2z2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eye" /></template>
<style>
.qfqcd2z2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9.75 9.75 0 0 1 18 0a9.75 9.75 0 0 1-18 0m7 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
