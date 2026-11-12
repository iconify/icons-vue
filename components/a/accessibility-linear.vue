<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="srxr8c13n"/><path class="iloc7qlea"/><path class="ntwgbdcqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:accessibility-linear" /></template>
<style>
.iloc7qlea {
  d: path("M18 10C18 10 14.4627 11.5 12 11.5C9.53727 11.5 6 10 6 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntwgbdcqi {
  d: path("M12 12V13.4522M12 13.4522C12 14.0275 12.1654 14.5906 12.4765 15.0745L15 19M12 13.4522C12 14.0275 11.8346 14.5906 11.5235 15.0745L9 19");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.srxr8c13n {
  d: path("M14 7C14 8.10457 13.1046 9 12 9C10.8954 9 10 8.10457 10 7C10 5.89543 10.8954 5 12 5C13.1046 5 14 5.89543 14 7Z");
}

</style>
