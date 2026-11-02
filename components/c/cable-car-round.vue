<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1eloobtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-car-round" /></template>
<style>
.b1eloobtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h6a7.25 7.25 0 0 1 0 10H9a7.25 7.25 0 0 1 0-10m-2 5h10M4 9l16-4m-8 2v4m-2-7h.01M14 3h.01");
}

</style>
