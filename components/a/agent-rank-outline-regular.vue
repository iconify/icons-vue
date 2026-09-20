<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ps-_1ne9q"/><path class="s_yfbmb1g"/><path class="krpni0u_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-rank-outline-regular" /></template>
<style>
.krpni0u_o {
  d: path("m7 22 5 -5 5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ps-_1ne9q {
  d: path("M13.5 3.33a3.5 3.5 0 1 1 -2.96 0");
}

.s_yfbmb1g {
  d: path("m7 17.5 5 -5 5 5");
}

</style>
