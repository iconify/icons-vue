<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhaehdczv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-round" /></template>
<style>
.mhaehdczv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2ZM3 7V5a2 2 0 0 1 2-2h2m4 0h2a2 2 0 0 1 2 2M3 11v2a2 2 0 0 0 2 2m14-6a2 2 0 0 1 2 2v2m0 4v2a2 2 0 0 1-2 2h-2m-8-2a2 2 0 0 0 2 2h2");
}

</style>
