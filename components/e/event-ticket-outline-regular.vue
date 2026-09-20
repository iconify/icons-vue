<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cdxhw-bno"/><path class="sunqexbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-ticket-outline-regular" /></template>
<style>
.cdxhw-bno {
  d: path("M3 7h18v3l-2 2 2 2v3H3v-3l2 -2 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sunqexbsa {
  d: path("M16 7v10");
}

</style>
