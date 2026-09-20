<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="esolkqbpc"/><path class="ncgg_vb-i"/><path class="ov-43hi-z"/><path class="c-pcdbceg"/><path class="hn-9k3ndx"/><path class="hbb998bpi"/><path class="r7ao24n4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:freezing-rain-duotone-regular" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.esolkqbpc {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hbb998bpi {
  d: path("m14 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.hn-9k3ndx {
  d: path("m8 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.ncgg_vb-i {
  fill: currentColor;
  d: path("m8 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ov-43hi-z {
  fill: currentColor;
  d: path("m14 16 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r7ao24n4h {
  d: path("M4 22h16");
}

</style>
