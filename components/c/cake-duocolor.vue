<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y8pz_j_an"/><path class="tgogfgkje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cake-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tgogfgkje {
  d: path("M4 21v-8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8M3 21h18M4 16s.5-1 2-1s2.5 2 4 2s2.5-2 4-2s2.5 2 4 2s2-1 2-1");
}

.y8pz_j_an {
  stroke-opacity: 0.4;
  d: path("M8 8v3m4-3v3m4-3v3M8 4h.01M12 4h.01M16 4h.01");
}

</style>
