<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ituq5cv8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flask" /></template>
<style>
.ituq5cv8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3v6L5 19c-.46.919.081 2 1 2h12c.919 0 1.46-1.081 1-2L14 9V3M8 3h8M7 15h10");
}

</style>
