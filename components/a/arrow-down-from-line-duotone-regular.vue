<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r4q1s-bug"/><path class="z3d6c58bu"/><path class="nz2n46bes"/><path class="t46_l1b3y"/><path class="o8adkomvn"/><path class="qrnoe1--b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-down-from-line-duotone-regular" /></template>
<style>
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

.o8adkomvn {
  d: path("M12 8v12");
}

.qrnoe1--b {
  d: path("m8 16 4 4 4 -4");
}

.r4q1s-bug {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t46_l1b3y {
  d: path("M7 4h10");
}

.z3d6c58bu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
