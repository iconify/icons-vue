<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="euj6eqbac"/><path class="moc63lp3w"/><path class="sv2vrddhu"/><path class="mg7aqnbsf"/><path class="it88l1wbh"/><path class="nbib5l08z"/><path class="cxyu2ib7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logprobs-duotone-thin" /></template>
<style>
.cxyu2ib7h {
  d: path("M17 7v12");
}

.euj6eqbac {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.it88l1wbh {
  d: path("M7 7v10");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.moc63lp3w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nbib5l08z {
  d: path("M12 7v14");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sv2vrddhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
