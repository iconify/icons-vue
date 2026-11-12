<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nderr86nc"/><path class="cja_agn5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coin-jar-duotone" /></template>
<style>
.cja_agn5e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12v2l-1 1c-.64.64-1 1.36-1 2v2a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-2c0-.64-.36-1.36-1-2l-1-1v-2m-9 0h10M6 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m7 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.nderr86nc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m7 2a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 12v1.586l.707.707C18.422 15.008 19 15.961 19 17v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2c0-1.039.578-1.992 1.293-2.707L7 13.586V12a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1");
}

</style>
