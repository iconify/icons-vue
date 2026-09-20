<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo-i6bqjc"/><path class="td_xqobtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clouds-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.td_xqobtu {
  d: path("M9 21a3.5 3.5 0 0 1 2 -6 4.5 4.5 0 0 1 8 -1 4.5 4.5 0 0 1 3 7Z");
}

.wo-i6bqjc {
  d: path("M2 14a3 3 0 0 1 2 -5.5 4 4 0 0 1 7.5 -1A4.5 4.5 0 0 1 15 14Z");
}

</style>
