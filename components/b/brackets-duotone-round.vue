<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt5htob7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-duotone-round" /></template>
<style>
.nt5htob7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7H6a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h1M17 7h1a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-1");
}

</style>
