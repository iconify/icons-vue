<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qqosr8ucg"/><path class="hp5p-wbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hp5p-wbnk {
  d: path("M13.707 8.707L12.414 10H14a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L11.586 12H10a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414M3 9h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m17 0h1a1 1 0 0 1 0 2h-1a1 1 0 0 1 0-2");
}

.qqosr8ucg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 19H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 3 16v-6c0-.155.036-.308.106-.447l2-4C5.643 4.478 6.652 3.001 8 3h8c1.348.001 2.357 1.478 2.894 2.553l2 4c.07.139.106.292.106.447v6c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1Z");
}

</style>
