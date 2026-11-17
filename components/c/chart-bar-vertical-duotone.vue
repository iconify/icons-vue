<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ee11mdbab"/><path class="t3ff4qb6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-vertical-duotone" /></template>
<style>
.ee11mdbab {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 4a2 2 0 0 1 2 2v14H9V6a2 2 0 0 1 2-2Zm3 6c0-.741.268-1.449.764-2H19a2 2 0 0 1 2 2v10h-5Zm-8 3v7H3v-7a2 2 0 0 1 2-2h2.236c.494.552.766 1.259.764 2");
}

.ft5dv1b6b {
  fill: none;
}

.t3ff4qb6i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20v-7a2 2 0 0 1 2-2h4V6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2h4a2 2 0 0 1 2 2v10zm6 0v-9m6 9V8");
}

</style>
