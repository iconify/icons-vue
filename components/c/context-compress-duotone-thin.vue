<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eri9pjq"/><path class="ta4vmeb9o"/><path class="vzegeabik"/><path class="svxrhubax"/><path class="haukdub-k"/><path class="kmu78qebm"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="qhy91zm_e"/><path class="a9xckwbov"/><path class="qlfruhq7c"/><path class="br_h3vzli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:context-compress-duotone-thin" /></template>
<style>
.a9xckwbov {
  d: path("m9 10 2 2 -2 2");
}

.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.br_h3vzli {
  d: path("m15 10 -2 2 2 2");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.e6eri9pjq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.haukdub-k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmu78qebm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qhy91zm_e {
  d: path("M6 12h5");
}

.qlfruhq7c {
  d: path("M13 12h5");
}

.svxrhubax {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ta4vmeb9o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzegeabik {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
