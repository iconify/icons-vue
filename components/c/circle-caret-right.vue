<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="i61nrl8do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-right" /></template>
<style>
.i61nrl8do {
  d: path("M16.7267 12.4699L8.78926 16.9316C8.43516 17.1306 8 16.8716 8 16.4617L8 7.5383C8 7.12844 8.43516 6.86937 8.78926 7.06842L16.7267 11.5301C17.0911 11.7349 17.0911 12.2651 16.7267 12.4699Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tx_ah59as {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

</style>
