<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="amk230bfn"/><path class="yca85s61c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-restore-duotone-round" /></template>
<style>
.amk230bfn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6");
}

.ft5dv1b6b {
  fill: none;
}

.yca85s61c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m2 2v8a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V8m-4 6l-3-3l-3 3m3-3v6");
}

</style>
