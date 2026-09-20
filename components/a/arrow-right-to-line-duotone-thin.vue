<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zitzxjbtk"/><path class="ypogw4bqt"/><path class="r5o-d4b5v"/><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="egsaq3b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-to-line-duotone-thin" /></template>
<style>
.egsaq3b2f {
  d: path("m12 8 4 4 -4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jka0cfj-k {
  d: path("M4 12h12");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.r5o-d4b5v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ypogw4bqt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zitzxjbtk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
