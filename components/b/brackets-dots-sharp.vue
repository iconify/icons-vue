<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sebt69wqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-dots-sharp" /></template>
<style>
.sebt69wqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3H3v18h3M18 3h3v18h-3M9 6h.01M15 6h.01M9 12h.01M15 12h.01M9 18h.01M15 18h.01");
}

</style>
