<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vul_uwbfe"/><path class="wxx-lxpns"/><path class="ashjd6b6l"/><path class="zo_lqebkt"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="jk6bn7bej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-remove-duotone-regular" /></template>
<style>
.ashjd6b6l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jk6bn7bej {
  d: path("M15.5 12h6");
}

.ldkstzszf {
  d: path("M3 16h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.qnmmmsbha {
  d: path("M3 11h11");
}

.vul_uwbfe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wxx-lxpns {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zo_lqebkt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
