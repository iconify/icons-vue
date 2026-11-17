<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k78r-xbki"/><path class="ux78ty71o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k78r-xbki {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 13h2c1.041 0 2.236.237 3 1l1 1c.764.763 1.959 1 3 1s2.236-.237 3-1l1-1c.764-.763 1.959-1 3-1h2v3a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

.ux78ty71o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm0 5h2c1.28 0 2.36.36 3 1l1 1c.64.64 1.72 1 3 1s2.36-.36 3-1l1-1c.64-.64 1.72-1 3-1h2");
}

</style>
