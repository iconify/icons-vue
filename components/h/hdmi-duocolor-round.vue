<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zzutjwbbr"/><path class="r50oh-b2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hdmi-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r50oh-b2a {
  d: path("M12 7h7a2 2 0 0 1 2 2v2l-4 6H7l-4-6V9a2 2 0 0 1 2-2z");
}

.zzutjwbbr {
  stroke-opacity: 0.4;
  d: path("M8 11h8");
}

</style>
