<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ps3wg5brq"/><path class="it78n3bnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.it78n3bnl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12v2l-2 2v5h12v-5l-2-2v-2m-9 0h10M6 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ps3wg5brq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m7 2a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 12v1.586l1.707 1.707A1 1 0 0 1 19 16v5a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-5c0-.265.105-.52.293-.707L7 13.586V12a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1");
}

</style>
