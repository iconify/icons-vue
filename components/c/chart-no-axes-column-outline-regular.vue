<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u66cvxjqz"/><path class="h-el3xdlg"/><path class="e9_u-df3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-no-axes-column-outline-regular" /></template>
<style>
.e9_u-df3m {
  d: path("M18 13v7");
}

.h-el3xdlg {
  d: path("M12 6v14");
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

</style>
