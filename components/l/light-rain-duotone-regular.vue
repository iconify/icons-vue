<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="esolkqbpc"/><path class="xvrtzwm1e"/><path class="s6yzsme1j"/><path class="c-pcdbceg"/><path class="yar83jxfe"/><path class="oqw_13bxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:light-rain-duotone-regular" /></template>
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

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqw_13bxd {
  d: path("m15 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.s6yzsme1j {
  fill: currentColor;
  d: path("m15 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xvrtzwm1e {
  fill: currentColor;
  d: path("m9 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yar83jxfe {
  d: path("m9 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
