<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-d7dab2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-o-duotone-round" /></template>
<style>
.c-d7dab2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3a6 6 0 0 0-6 6v6a6 6 0 0 0 6 6m0-18a6 6 0 0 1 6 6v6a6 6 0 0 1-6 6");
}

</style>
