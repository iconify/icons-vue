<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="etbs71upp"/><path class="aoyy04bai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-duotone-sharp" /></template>
<style>
.aoyy04bai {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18v-8l3-6h10l3 6v8zm2 0h2v2H6Zm10 0h2v2h-2ZM3 10h18M8 14h.01M16 14h.01");
}

.etbs71upp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 10c0-.155.036-.308.106-.447l3-6A1 1 0 0 1 7 3h10c.379 0 .725.214.894.553l3 6c.07.139.106.292.106.447v8a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
