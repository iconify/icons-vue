<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cd3ob020j"/><path class="v8mk04bql"/><path class="mpjdm200q"/><path class="qrn866ncb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feature-drift-duotone-regular" /></template>
<style>
.cd3ob020j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qrn866ncb {
  d: path("m10 9 3 3 3 -3 3 3");
}

.v8mk04bql {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
