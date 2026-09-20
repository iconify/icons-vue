<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gf0hswvuq"/><path class="pfjq2-b9j"/><path class="b5ak1dhxf"/><path class="kw50e_bvi"/><path class="k35wv8y0z"/><path class="eojr-cxjg"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-id-duotone-regular" /></template>
<style>
.a-r3j5f7z {
  d: path("M3 16v4h5");
}

.a71lhwniq {
  d: path("M16 4h5v4");
}

.b5ak1dhxf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dxxnlbcax {
  d: path("M3 8V4h5");
}

.dy-bj6bwq {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.eojr-cxjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gf0hswvuq {
  fill: currentColor;
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k35wv8y0z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kw50e_bvi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pfjq2-b9j {
  fill: currentColor;
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u84sg0ngq {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xt7079b9x {
  d: path("M16 20h5v-4");
}

</style>
