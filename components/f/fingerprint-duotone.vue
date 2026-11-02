<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4t73obvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fingerprint-duotone" /></template>
<style>
.y4t73obvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 17v-3a8.062 8.062 0 0 1 12-8m3 3a8.1 8.1 0 0 1 1 3v4m-8-3v5m-4 1v-6a4 4 0 1 1 8 0v3");
}

</style>
