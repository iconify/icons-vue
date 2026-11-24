<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r0ei7n78p"/><path class="suikiejqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:control-tower-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r0ei7n78p {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h18l-4 6h-2v8H9v-8H7Z");
}

.suikiejqt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18l-4 6H7zm6 6v8m6-8v8M3 21h18M12 7V3M8 7l2 6m6-6l-2 6");
}

</style>
