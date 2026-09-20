<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vss30cbwe"/><path class="qup_krbff"/><path class="z7-y49bgo"/><path class="b5bbp_b6e"/><path class="u2z_81bft"/><path class="xbibi3o1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:co-two-duotone-thin" /></template>
<style>
.b5bbp_b6e {
  d: path("M5 18a4 4 0 0 1 2 -7 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qup_krbff {
  fill: currentColor;
  d: path("M7.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u2z_81bft {
  d: path("M7.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vss30cbwe {
  fill: currentColor;
  d: path("M5 18a4 4 0 0 1 2 -7 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xbibi3o1e {
  d: path("M13 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z7-y49bgo {
  fill: currentColor;
  d: path("M13 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
