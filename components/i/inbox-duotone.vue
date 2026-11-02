<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ctc5lfz7i"/><path class="kz5g6ac3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duotone" /></template>
<style>
.ctc5lfz7i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 12c1.039 0 1.992.578 2.707 1.293l1 1c.313.312.825.707 1.293.707h2c.468 0 .98-.395 1.293-.707l1-1C16.008 12.578 16.961 12 18 12h3a1 1 0 0 1 1 1v5a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-5a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.kz5g6ac3r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0 7h3c.64 0 1.36.36 2 1l1 1c.64.64 1.36 1 2 1h2c.64 0 1.36-.36 2-1l1-1c.64-.64 1.36-1 2-1h3");
}

</style>
