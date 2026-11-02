<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmtd3vrky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lasso" /></template>
<style>
.bmtd3vrky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12a4.9 4.9 0 0 1-1-3c0-3.314 3.582-6 8-6s8 2.686 8 6s-3.582 6-8 6c-1.45 0-2.757-.44-4-1m-4 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2c0 2 1 4 3 5");
}

</style>
