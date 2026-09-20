<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e8rfc8bkg"/><path class="fl4-3wbrs"/><path class="ffr4b6b1w"/><path class="mvm7r4bea"/><path class="jinvu3zma"/><path class="uac-t6brn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ladle-duotone-thin" /></template>
<style>
.e8rfc8bkg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ffr4b6b1w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 14c1 -5 -1 -10 -4 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fl4-3wbrs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 14a4 4 0 0 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jinvu3zma {
  d: path("M16 14a4 4 0 0 1 -8 0");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.uac-t6brn {
  d: path("M16 14c1 -5 -1 -10 -4 -11");
}

</style>
