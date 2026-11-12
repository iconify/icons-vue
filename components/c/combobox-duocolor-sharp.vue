<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ibvz_rbnu"/><path class="oe6q8hr5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:combobox-duocolor-sharp" /></template>
<style>
.ibvz_rbnu {
  stroke-opacity: 0.4;
  d: path("m14 6l2 2l2-2M7 18h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe6q8hr5d {
  d: path("M3 3h18v8H3Zm0 12h18v6H3Zm4-9v2");
}

</style>
