<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkwkxlv2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3" /></template>
<style>
.lkwkxlv2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20v-5c0-.64.36-1.36 1-2l3-3a1.414 1.414 0 0 1 2 0l3 3c.64.64 1 1.36 1 2v5m-8-8V6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v14");
}

</style>
