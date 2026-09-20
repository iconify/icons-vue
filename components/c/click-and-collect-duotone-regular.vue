<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e06o29xir"/><path class="am603abae"/><path class="whur97baj"/><path class="f2sbyxnyq"/><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="kn8ghfb-y"/><path class="s-gg8lbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:click-and-collect-duotone-regular" /></template>
<style>
.am603abae {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v14h16V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e06o29xir {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f2sbyxnyq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 15 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kn8ghfb-y {
  d: path("M12 11v6.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-gg8lbxh {
  d: path("m9.5 15 2.5 2.5 2.5 -2.5");
}

.tp7101bon {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

.whur97baj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yb0d-pkkp {
  d: path("M4 8v14h16V8");
}

</style>
