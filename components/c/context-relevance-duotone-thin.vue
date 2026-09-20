<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="tdygnegpg"/><path class="nzgezp68k"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="nesadtboq"/><path class="mm9i2knor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-relevance-duotone-thin" /></template>
<style>
.dba5rjonf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.mm9i2knor {
  d: path("M11.5 7H14v6h-2.5");
}

.nesadtboq {
  d: path("M8.5 7H6v6h2.5");
}

.nzgezp68k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 7H14v6h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tdygnegpg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 7H6v6h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl5hlnbpt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
