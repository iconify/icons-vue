<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rd3_-g5sv"/><path class="gwny-o4ct"/><path class="wlp3ibbib"/><path class="tqskisbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assignment-duotone-regular" /></template>
<style>
.gwny-o4ct {
  d: path("M2 20V6h7l2 2h11v12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rd3_-g5sv {
  fill: currentColor;
  d: path("M2 20V6h7l2 2h11v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tqskisbpb {
  d: path("M6 16h8");
}

.wlp3ibbib {
  d: path("M6 13h12");
}

</style>
