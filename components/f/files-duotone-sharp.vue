<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pauz5bbko"/><path class="kc_-307vq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:files-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kc_-307vq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6H3v15h10V11M8 6l5 5M8 6v5h5m-2-8h5m0 0l5 5m-5-5v5h5m0 0v10h-4");
}

.pauz5bbko {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5c.265 0 .52.105.707.293l5 5A1 1 0 0 1 14 11v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Zm0 6h4L8 7Z");
}

</style>
