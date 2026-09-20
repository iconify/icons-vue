<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="d_56kfbkh"/><path class="wc2ol_sxo"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="strt8mboj"/><path class="p8yct170k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keyword-search-duotone-thin" /></template>
<style>
.d_56kfbkh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

.p8yct170k {
  d: path("M7 12h6");
}

.strt8mboj {
  d: path("M7 8h6");
}

.wc2ol_sxo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zl5hlnbpt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
