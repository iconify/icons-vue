<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s2_e_1d6x"/><path class="c102occgv"/><path class="jdr327xaa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamond-dot-sharp-two-tone" /></template>
<style>
.c102occgv {
  d: path("M12 2L22 12L12 22L2 12L12 2Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jdr327xaa {
  fill: currentColor;
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
  stroke: none;
}

.s2_e_1d6x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.7071 1.2929L22.7071 11.2929C22.8946 11.4804 23 11.7348 23 12C23 12.2652 22.8946 12.5196 22.7071 12.7071L12.7071 22.7071C12.5196 22.8946 12.2652 23 12 23C11.7348 23 11.4804 22.8946 11.2929 22.7071L1.2929 12.7071C1.1054 12.5196 1 12.2652 1 12C1 11.7348 1.1054 11.4804 1.2929 11.2929L11.2929 1.2929C11.4804 1.1054 11.7348 1 12 1C12.2652 1 12.5196 1.1054 12.7071 1.2929Z");
  stroke: none;
}

</style>
