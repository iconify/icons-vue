<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ee11mdbab"/><path class="pecyojbct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-stacked-duotone-round" /></template>
<style>
.ee11mdbab {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 4a2 2 0 0 1 2 2v14H9V6a2 2 0 0 1 2-2Zm3 6c0-.741.268-1.449.764-2H19a2 2 0 0 1 2 2v10h-5Zm-8 3v7H3v-7a2 2 0 0 1 2-2h2.236c.494.552.766 1.259.764 2");
}

.ft5dv1b6b {
  fill: none;
}

.pecyojbct {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-5a4 4 0 0 1 4-4h2V7a3 3 0 0 1 6 0v1h2a4 4 0 0 1 4 4v8zm6 0v-9m6 9V8M3 15h6m0-3h6m0 2h6");
}

</style>
