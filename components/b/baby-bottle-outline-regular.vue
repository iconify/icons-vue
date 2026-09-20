<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wdl213b6n"/><path class="cfd43lbgp"/><path class="yhnjhi90f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baby-bottle-outline-regular" /></template>
<style>
.cfd43lbgp {
  d: path("M7 13h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wdl213b6n {
  d: path("M7 21V9h10v12Z");
}

.yhnjhi90f {
  d: path("M10 9V6.5a2 2 0 0 1 4 0V9");
}

</style>
