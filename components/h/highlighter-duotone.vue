<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tudj5zbvr"/><path class="nkta-tnve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nkta-tnve {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l6-6a1.414 1.414 0 0 1 2 0l4 4a1.414 1.414 0 0 1 0 2l-6 6zm1 1l-5 5v2a1 1 0 0 0 1 1h4l4-4");
}

.tudj5zbvr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.293 4.293a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414l-6 6a1 1 0 0 1-1.414 0l-6-6a.997.997 0 0 1 0-1.414Z");
}

</style>
