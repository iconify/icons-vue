<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="jlpxneb5g"/><path class="h7bcztycq"/><path class="pqrd0wbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:barcode-scan-outline-regular" /></template>
<style>
.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

</style>
