<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lewyoxk4j"/><path class="ut4srhbgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lewyoxk4j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 12v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1Z");
}

.ut4srhbgd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H3V5h18v6M3 5l6 6h6l6-6m-6 13h6m-3-3v6");
}

</style>
