<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qptp-ac0t"/><path class="wel0bjp6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qptp-ac0t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18.828 19.828A3.97 3.97 0 0 1 16 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4ZM14 9h2a4 4 0 0 1 4 4v2Z");
}

.wel0bjp6e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.828 19.828A4 4 0 0 1 16 21H8a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m6 0h2a4 4 0 0 1 4 4v2M9.172 4.172A4 4 0 0 1 16 7v2M2 3l19 19");
}

</style>
