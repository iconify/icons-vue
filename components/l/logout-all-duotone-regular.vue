<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yf9gwfh6d"/><path class="w8-9e34jo"/><path class="kx2jyqbyy"/><path class="b42s0fbnt"/><path class="o2rxerunx"/><path class="wt76_hbmn"/><path class="l9cf9bbmd"/><path class="plqv1xi7k"/><path class="j_z-vb9qy"/><path class="xvmft_b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:logout-all-duotone-regular" /></template>
<style>
.b42s0fbnt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 15h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_z-vb9qy {
  d: path("M10 15h10");
}

.kx2jyqbyy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 6.5 20 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9cf9bbmd {
  d: path("M10 9h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2rxerunx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.5 12.5 20 15l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.plqv1xi7k {
  d: path("M17.5 6.5 20 9l-2.5 2.5");
}

.w8-9e34jo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt76_hbmn {
  d: path("M9 3H3v18h6");
}

.xvmft_b5k {
  d: path("M17.5 12.5 20 15l-2.5 2.5");
}

.yf9gwfh6d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3H3v18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
