<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iqzdkybgr"/><path class="ykxqiacwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iqzdkybgr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h3a4 4 0 0 1 4 4v3Zm7 14c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V8a3.95 3.95 0 0 1 .716-2.284L18 17Z");
}

.ykxqiacwp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h2a4 4 0 0 1 4 4v3m0 6v1c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V8c0-.85.265-1.637.716-2.284M3 2l19 19");
}

</style>
