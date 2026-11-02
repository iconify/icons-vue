<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p6d3pppgq"/><path class="jp0baob-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-edit-duocolor-sharp" /></template>
<style>
.jp0baob-m {
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p6d3pppgq {
  stroke-opacity: 0.4;
  d: path("M9 18v-2l4-4l2 2l-4 4Z");
}

</style>
