<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fa1ifxb5g"/><path class="igclk3bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-duotone-round" /></template>
<style>
.fa1ifxb5g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 16v-6c0-.155.036-.308.106-.447l2-4C5.848 4.069 7.307 3 9 3h6c1.693 0 3.152 1.069 3.894 2.553l2 4c.07.139.106.292.106.447v6a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3");
}

.ft5dv1b6b {
  fill: none;
}

.igclk3bhz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18H6a2 2 0 0 1-2-2v-6l2-4c.613-1.226 1.774-2 3-2h6c1.226 0 2.387.774 3 2l2 4v6a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 10h18M8 14h.01M16 14h.01");
}

</style>
