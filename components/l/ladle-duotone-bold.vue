<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gtj8b-brg"/><path class="i8u6kml0k"/><path class="mc9s3ubqd"/><path class="mvm7r4bea"/><path class="jinvu3zma"/><path class="uac-t6brn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ladle-duotone-bold" /></template>
<style>
.gtj8b-brg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i8u6kml0k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14a4 4 0 0 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jinvu3zma {
  d: path("M16 14a4 4 0 0 1 -8 0");
}

.mc9s3ubqd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14c1 -5 -1 -10 -4 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uac-t6brn {
  d: path("M16 14c1 -5 -1 -10 -4 -11");
}

</style>
