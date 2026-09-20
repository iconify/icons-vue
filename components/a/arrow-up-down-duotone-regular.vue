<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw099db1h"/><path class="yitei-bhk"/><path class="nz2n46bes"/><path class="r7xk8o29f"/><path class="h3z-uye4u"/><path class="qrnoe1--b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-down-duotone-regular" /></template>
<style>
.h3z-uye4u {
  d: path("m8 8 4 -4 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nz2n46bes {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrnoe1--b {
  d: path("m8 16 4 4 4 -4");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.uw099db1h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yitei-bhk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
