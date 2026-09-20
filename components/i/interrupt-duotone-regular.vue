<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vnfvzfije"/><path class="ef5ubjb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:interrupt-duotone-regular" /></template>
<style>
.ef5ubjb0b {
  d: path("M18 2 8 12h5l-8 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vnfvzfije {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 2 8 12h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
