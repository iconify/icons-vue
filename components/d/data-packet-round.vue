<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2uyqacfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:data-packet-round" /></template>
<style>
.n2uyqacfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm0 0h12m-8 4v3m4-3v3M3 8h2m-2 4h2m-2 4h2");
}

</style>
