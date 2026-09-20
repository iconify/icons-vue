<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nguhiybnr"/><path class="r411km12t"/><path class="ez1_3xbuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drill-outline-regular" /></template>
<style>
.ez1_3xbuo {
  d: path("M14 8h7");
}

.nguhiybnr {
  d: path("M4 5h10v6H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r411km12t {
  d: path("M6 11v9h4v-9");
}

</style>
