<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mfg4gqx2s"/><path class="pab-zmevq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-music-fill" /></template>
<style>
.mfg4gqx2s {
  fill: currentColor;
  d: path("M23 15C23 17.2091 21.2091 19 19 19C16.7909 19 15 17.2091 15 15C15 12.7909 16.7909 11 19 11C21.2091 11 23 12.7909 23 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pab-zmevq {
  d: path("M2 6H16M2 12H10M2 18H10M22 15V6");
}

</style>
