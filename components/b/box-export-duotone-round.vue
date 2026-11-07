<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="biulmpbwn"/><path class="ll4clabto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-export-duotone-round" /></template>
<style>
.biulmpbwn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 11.51V20a2.242 2.242 0 0 1-3.236 2.011l-6.092-3.008A3 3 0 0 1 2 16.313V7.687c0-1.141.648-2.184 1.672-2.69l7-3.456a3 3 0 0 1 2.656 0l6.322 3.121a1.988 1.988 0 0 1 0 3.565Z");
}

.ft5dv1b6b {
  fill: none;
}

.ll4clabto {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12V7.687a2 2 0 0 0-1.114-1.793L16.5 4.222m0 0l-3.614-1.785a2 2 0 0 0-1.772 0l-7 3.457A2 2 0 0 0 3 7.687v8.626a2 2 0 0 0 1.114 1.793l6.093 3.008A1.243 1.243 0 0 0 12 20v-9.111M3.32 6.602L12 10.89l8.68-4.287M18 21l3-3l-3-3m3 3h-6");
}

</style>
