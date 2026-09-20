<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n92hyrp1a"/><path class="ci868tbkg"/><path class="zc48m34dw"/><path class="fbw2ldgtv"/><path class="pmuiqo95v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:control-plane-outline-regular" /></template>
<style>
.ci868tbkg {
  d: path("M2 7h7");
}

.fbw2ldgtv {
  d: path("M12 10v7");
}

.n92hyrp1a {
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.zc48m34dw {
  d: path("M15 7h7");
}

</style>
