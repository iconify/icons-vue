<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xvfhj-u6p"/><path class="yhkadmb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-warning-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xvfhj-u6p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 21H8a4 4 0 0 1-4-4v-5.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0l4 3.5A4 4 0 0 1 20 11.815V17a4 4 0 0 1-4 4");
}

.yhkadmb9l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H8a4 4 0 0 1-4-4v-5.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0l4 3.5A4 4 0 0 1 20 11.815V17a4 4 0 0 1-4 4zm0-10v3m0 3h.01");
}

</style>
