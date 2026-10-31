<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="aa0xg1tem"/><path class="cdc-xobvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-two-tone" /></template>
<style>
.aa0xg1tem {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M5 1L11 1C13.2092 1 15 2.7908 15 5L15 22C15 22.5523 14.5523 23 14 23L2 23C1.4477 23 1 22.5523 1 22L1 5C1 2.7908 2.7908 1 5 1ZM18 5L22 5C22.5523 5 23 5.4477 23 6L23 8.5C23 9.8807 21.8807 11 20.5 11L19.5 11C18.1193 11 17 9.8807 17 8.5L17 6C17 5.4477 17.4477 5 18 5Z");
  stroke: none;
}

.cdc-xobvu {
  d: path("M5 2L11 2C12.6569 2 14 3.3431 14 5L14 22L2 22L2 5C2 3.3431 3.3431 2 5 2ZM14 22L22 22M14 17L18 17C19.1046 17 20 16.1046 20 15L20 10M18 6L22 6L22 8.5C22 9.3284 21.3284 10 20.5 10L19.5 10C18.6716 10 18 9.3284 18 8.5L18 6ZM22 6L22 4M18 6L18 4M9 8L6 12L10 12L7 16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
