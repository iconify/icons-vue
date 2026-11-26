<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c2pbmbb6m"/><path class="cjkqb5b7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hexagon-third-sharp" /></template>
<style>
.c2pbmbb6m {
  d: path("M12 2L21 6.8809L21 17.1191L12 22L3 17.1191L3 6.8809L12 2Z");
}

.cjkqb5b7v {
  d: path("M12 6.5504L17 9.262L17 14.738L12 12Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
