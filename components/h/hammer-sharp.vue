<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0p12bb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-sharp" /></template>
<style>
.u0p12bb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h2l2 2l3-3l-2-2V7l-2-2c-1.28-1.28-2.72-2-4-2zm6 9l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
