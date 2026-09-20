<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gxonvhq6b"/><path class="sbpsi82ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-up-duotone-regular" /></template>
<style>
.gxonvhq6b {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 15 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sbpsi82ym {
  d: path("m5 15 7 -7 7 7");
}

</style>
