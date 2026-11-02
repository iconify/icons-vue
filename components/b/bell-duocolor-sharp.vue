<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v6dd933zq"/><path class="umvva7kfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.umvva7kfu {
  d: path("M12 17H4v-2c0-1 1-1 1-2v-3a7 7 0 0 1 14 0v3c0 1 1 1 1 2v2z");
}

.v6dd933zq {
  stroke-opacity: 0.4;
  d: path("M9 17v1a3 3 0 0 0 6 0v-1");
}

</style>
