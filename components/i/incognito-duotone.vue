<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vhmds_zmw"/><path class="tfbpjbezx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:incognito-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tfbpjbezx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6 10l2-5c.242-.604.638-1 1-1h6c.362 0 .758.396 1 1l2 5M3 10h18M4 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-4 0a2 2 0 1 1 4 0");
}

.vhmds_zmw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.072 4.629C7.394 3.823 8.056 3 9 3h6c.944 0 1.606.823 1.928 1.629l2 5A.998.998 0 0 1 18 11H6a1 1 0 0 1-.928-1.371Z");
}

</style>
