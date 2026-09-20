<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fqboz3btt"/><path class="tgy6cdcqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:action-duotone-regular" /></template>
<style>
.fqboz3btt {
  fill: currentColor;
  d: path("m8 3 9 9 -9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tgy6cdcqx {
  d: path("m8 3 9 9 -9 9Z");
}

</style>
