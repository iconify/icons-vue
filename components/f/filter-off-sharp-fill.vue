<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="atfan1pfn"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-off-sharp-fill" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.atfan1pfn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 20.618L10.4472 21.8944C9.7823 22.2269 9 21.7434 9 21L9 14.6569L11 14.6569L13 16.6569L13 13.0001L15 15.0001L15 19.0001C15 19.3789 14.786 19.7251 14.4472 19.8945ZM5.6569 2L21 2C21.8451 2 22.3092 2.9833 21.7719 3.6357L15.2329 11.576Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
