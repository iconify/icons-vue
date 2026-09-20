<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uy91f4czm"/><path class="fynjz_bjk"/><path class="zpp3fehhr"/><path class="jm1gdl4et"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-toolbelt-outline-regular" /></template>
<style>
.fynjz_bjk {
  d: path("M7.5 17a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

.jm1gdl4et {
  d: path("M14 12v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uy91f4czm {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

.zpp3fehhr {
  d: path("M10 12v3");
}

</style>
