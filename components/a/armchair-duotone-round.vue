<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pjr12pbke"/><path class="x9kgnzbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pjr12pbke {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 12h4a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 21 11v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 19H8a5 5 0 0 1-5-5v-3a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1");
}

.x9kgnzbuh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11v3a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4v-3a2 2 0 1 0-4 0a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 7v2m12-2v2M6 9V8a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v1");
}

</style>
