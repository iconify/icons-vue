<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kjg8nqb5h"/><path class="d223d_x9q"/><path class="uhawluh-v"/><path class="cpmzr29ux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:encoder-only-duotone-regular" /></template>
<style>
.cpmzr29ux {
  d: path("m16 8 4 4 -4 4 -4 -4Z");
}

.d223d_x9q {
  d: path("M3 12h6");
}

.kjg8nqb5h {
  fill: currentColor;
  d: path("m16 8 4 4 -4 4 -4 -4Z");
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

.uhawluh-v {
  d: path("M6.5 9.5 9 12l-2.5 2.5");
}

</style>
