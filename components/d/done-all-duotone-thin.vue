<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a8o-bmuyf"/><path class="sf2p08-cs"/><path class="r1gclvbbm"/><path class="ks2swpbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:done-all-duotone-thin" /></template>
<style>
.a8o-bmuyf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ks2swpbkw {
  d: path("m9 12 5 5 8 -8");
}

.r1gclvbbm {
  d: path("m2 12 5 5 8 -8");
}

.sf2p08-cs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 5 5 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
