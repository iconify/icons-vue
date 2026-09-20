<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tgd916uxo"/><path class="ebby1xbgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:draft-model-outline-regular" /></template>
<style>
.ebby1xbgn {
  d: path("M16.5 6.5 22 12l-5.5 5.5L11 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tgd916uxo {
  d: path("M5 9.5 7.5 12 5 14.5 2.5 12Z");
}

</style>
