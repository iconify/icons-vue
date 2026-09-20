<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eztihp87k"/><path class="xct1uqbtr"/><path class="nmesolb_v"/><path class="u66cvxjqz"/><path class="h-el3xdlg"/><path class="e9_u-df3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-no-axes-column-duotone-regular" /></template>
<style>
.e9_u-df3m {
  d: path("M18 13v7");
}

.eztihp87k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-el3xdlg {
  d: path("M12 6v14");
}

.nmesolb_v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u66cvxjqz {
  d: path("M6 10v10");
}

.xct1uqbtr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
