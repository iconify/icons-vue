<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bm87u4fvu"/><path class="v-rljbbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:double-check-two-tone" /></template>
<style>
.bm87u4fvu {
  stroke-opacity: 0.4;
  d: path("M2.5 11L7.16667 16L16.5 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-rljbbxp {
  d: path("M21.5 11L15.5 18L13.5 16");
}

</style>
