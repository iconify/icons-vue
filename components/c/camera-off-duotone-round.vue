<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hn_4a6bwe"/><path class="vzqw79oqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hn_4a6bwe {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 16L9.539 4.539C9.964 4.235 10.468 4 11 4h2c.773 0 1.472.473 2 1l2 2a4 4 0 0 1 4 4Zm-2.354 3.646A4 4 0 0 1 17 20H7a4 4 0 0 1-4-4v-5a4.006 4.006 0 0 1 3.101-3.899Z");
}

.vzqw79oqs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.54 4.54c.488-.35.995-.54 1.46-.54h2c.64 0 1.36.36 2 1l2 2a4 4 0 0 1 4 4v5m-2.354 3.646A4 4 0 0 1 17 20H7a4 4 0 0 1-4-4v-5c0-1.9 1.325-3.49 3.101-3.899M9.88 10.88a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

</style>
