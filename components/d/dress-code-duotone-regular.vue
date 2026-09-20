<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g6o2__b5i"/><path class="v24uwtnyd"/><path class="pteisib7h"/><path class="geztznlon"/><path class="f0k-qn7fa"/><path class="zicuro7zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dress-code-duotone-regular" /></template>
<style>
.f0k-qn7fa {
  d: path("m20 7 -4 4 4 4Z");
}

.g6o2__b5i {
  fill: currentColor;
  d: path("m4 7 4 4 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.geztznlon {
  d: path("m4 7 4 4 -4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pteisib7h {
  fill: currentColor;
  d: path("M10 8h4v6h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v24uwtnyd {
  fill: currentColor;
  d: path("m20 7 -4 4 4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zicuro7zb {
  d: path("M10 8h4v6h-4Z");
}

</style>
