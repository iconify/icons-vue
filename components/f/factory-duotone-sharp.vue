<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eqct2-mvg"/><path class="amuhq95gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:factory-duotone-sharp" /></template>
<style>
.amuhq95gv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M5 21V3h4v9l5-3v3l5-3v12M8 16h.01M12 16h.01M16 16h.01");
}

.eqct2-mvg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v7.234l3.486-2.091A.997.997 0 0 1 15 9v1.234l3.486-2.091A.997.997 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
