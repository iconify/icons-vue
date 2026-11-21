<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u76bhiy6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:film-scan-sharp" /></template>
<style>
.u76bhiy6y {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 21H3V3H13M8 3V21M3 12H13M3 7.5H8M3 16.5H8M13 1V23M17 2V11M17 22V13M21 21V17M21 15V9M21 7V3");
}

</style>
