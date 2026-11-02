<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzvr2u07d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-exit-duocolor-round" /></template>
<style>
.kzvr2u07d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8h1a4 4 0 0 0 4-4V3m8 0v1a4 4 0 0 0 4 4h1m0 8h-1a4 4 0 0 0-4 4v1m-8 0v-1a4 4 0 0 0-4-4H3");
}

</style>
