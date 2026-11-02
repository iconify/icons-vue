<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cftlv9b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-duotone-round" /></template>
<style>
.cftlv9b_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 16l3-3a2.83 2.83 0 0 1 4 0a2.83 2.83 0 0 0 4 0l7-7M3 4v12a4 4 0 0 0 4 4h14");
}

</style>
