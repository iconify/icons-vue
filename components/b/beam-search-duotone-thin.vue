<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwsytmgiu"/><path class="egcx08b2c"/><path class="trca3pm9n"/><path class="j569280wv"/><path class="ldxs-ebdf"/><path class="ege_vlbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:beam-search-duotone-thin" /></template>
<style>
.egcx08b2c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ege_vlbjp {
  d: path("m8 12 6 6h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwsytmgiu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h5l6 -6h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j569280wv {
  d: path("M3 12h5l6 -6h7");
}

.ldxs-ebdf {
  d: path("M8 12h13");
}

.trca3pm9n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 6 6h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
