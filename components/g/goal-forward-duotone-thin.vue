<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l65brscyv"/><path class="rsu38odap"/><path class="jeb_6eb2t"/><path class="jf4621b2f"/><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="bp52f-cpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:goal-forward-duotone-thin" /></template>
<style>
.bp52f-cpd {
  d: path("m11 6 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hspeesv2z {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

.jeb_6eb2t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 20.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jf4621b2f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l65brscyv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsu38odap {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tv6hbrcra {
  d: path("M8.5 20.5h7");
}

.ujt25lh2u {
  d: path("M12 15v5.5");
}

</style>
