<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzf60ab3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-percent" /></template>
<style>
.uzf60ab3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 7l3 3c.64.64 1 1.36 1 2v7a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-7c0-.64.36-1.36 1-2l6-6a1.414 1.414 0 0 1 2 0zm-2 5l-4 4m0-4h.01M14 16h.01");
}

</style>
