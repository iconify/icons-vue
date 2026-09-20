<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cus5btazq"/><path class="ytauj3b5f"/><path class="p8a31xr4o"/><path class="wn519caci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:decrypt-outline-regular" /></template>
<style>
.cus5btazq {
  d: path("M2 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8a31xr4o {
  d: path("M16 12h6");
}

.wn519caci {
  d: path("m19 9 3 3 -3 3");
}

.ytauj3b5f {
  d: path("M4 10a3 3 0 0 1 5.12 -2.12");
}

</style>
