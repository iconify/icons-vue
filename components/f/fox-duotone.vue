<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j80eyhprs"/><path class="y3-ncereq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j80eyhprs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m19 10l1 3l-7 7a1.415 1.415 0 0 1-2 0l-7-7l1-3V4c0-.369.631-.369 1 0l3 3c.521.52 1.237 1 2 1h2c.763 0 1.479-.48 2-1l3-3c.369-.369 1-.369 1 0Z");
}

.y3-ncereq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m19 10l1 3l-7 7a1.414 1.414 0 0 1-2 0l-7-7l1-3V4c0-.369.631-.369 1 0l3 3c.64.64 1.36 1 2 1h2c.64 0 1.36-.36 2-1l3-3c.369-.369 1-.369 1 0zM9 12l1 1m5-1l-1 1m-2 3h.01");
}

</style>
