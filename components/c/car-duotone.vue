<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lpw1poj0r"/><path class="jng2y1b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jng2y1b4r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18H6a2 2 0 0 1-2-2v-6l2-4c.613-1.226 1.387-2 2-2h8c.613 0 1.387.774 2 2l2 4v6a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 10h18M8 14h.01M16 14h.01");
}

.lpw1poj0r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 19a3 3 0 0 1-3-3v-6c0-.155.036-.308.106-.447l2-4C5.643 4.478 6.652 3.001 8 3h8c1.348.001 2.357 1.478 2.894 2.553l2 4c.07.139.106.292.106.447v6a3 3 0 0 1-3 3Z");
}

</style>
