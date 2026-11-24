<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="umqsb-24u"/><path class="n_oe8gbdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fire-station-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n_oe8gbdt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v16M3 21h18M6 21v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3m4 0v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3M12 6c.225 1.125.9 2.025 1.8 2.7c.675.675.9 1.575.9 2.7a2.7 2.7 0 1 1-5.4 0c0-.675.225-1.125.45-1.35m0 0a.9.9 0 1 0 1.8 0c0-.675-.225-.9-.45-1.35c-.45-.9-.225-1.8.9-2.7");
}

.umqsb-24u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 21V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v16Z");
}

</style>
