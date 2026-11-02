<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1v41vl7a"/><path class="fo6ymko1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off-duotone" /></template>
<style>
.fo6ymko1a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6c-2.074 1.445-3 4.28-3 7a8 8 0 0 0 8 8c2.72 0 5.555-.926 7-3m1-5a8 8 0 0 0-8-8M3 6l2-2m13-1l3 3M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.l1v41vl7a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3.708 9.496c1.934-4.578 7.216-6.721 11.795-4.786a9 9 0 0 1 4.787 11.793A9 9 0 0 1 8.497 21.29c-4.578-1.934-6.724-7.215-4.789-11.794");
}

</style>
