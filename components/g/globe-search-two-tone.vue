<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k0aallhpc"/><path class="o5jc5ndza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-search-two-tone" /></template>
<style>
.k0aallhpc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C18.0751 1 23 5.9249 23 12L8 12C8 15.5 9.3333 19 12 22L12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5jc5ndza {
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12M2 12L22 12M12 2C14.6667 5 16 8.5 16 12M12 2C9.33333 5 8 8.5 8 12C8 15.5 9.33333 19 12 22M21 18.5C21 19.8807 19.8807 21 18.5 21C17.1193 21 16 19.8807 16 18.5C16 17.1193 17.1193 16 18.5 16C19.8807 16 21 17.1193 21 18.5ZM20.5 20.5L22 22");
}

</style>
