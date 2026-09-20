<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rk-733byh"/><path class="zdfu0fbuo"/><path class="s4m8c10_q"/><path class="d6785mbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-sankey-duotone-regular" /></template>
<style>
.d6785mbmg {
  d: path("M4 18h6l4 -4h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rk-733byh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h6l4 4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s4m8c10_q {
  d: path("M4 6h6l4 4h6");
}

.zdfu0fbuo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h6l4 -4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
