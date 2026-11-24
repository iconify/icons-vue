<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ob2--58tq"/><path class="gcgmn5bkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:city-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gcgmn5bkr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M9 21V3h6v18M12 7h.01M12 11h.01M12 15h.01M6 13h.01M6 17h.01M18 17h.01M9 9H3v12m12-8h6v8");
}

.ob2--58tq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3h6v18H9Z");
}

</style>
