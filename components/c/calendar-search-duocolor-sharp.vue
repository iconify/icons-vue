<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mx73lcb8b"/><path class="jp0baob-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-duocolor-sharp" /></template>
<style>
.jp0baob-m {
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16");
}

.mx73lcb8b {
  stroke-opacity: 0.4;
  d: path("M9 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
