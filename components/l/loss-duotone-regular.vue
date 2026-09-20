<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="jj48i0bjg"/><path class="hq4sskbcg"/><path class="crv4i00bu"/><path class="wy8w_b5cr"/><path class="nzwwf5-_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:loss-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.hq4sskbcg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 5 6 6 3 3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jj48i0bjg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzwwf5-_s {
  d: path("m6 5 6 6 3 3h5");
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy8w_b5cr {
  d: path("M4 21h18");
}

</style>
