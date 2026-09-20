<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x87wa6b5t"/><path class="lx3jyybfn"/><path class="gf7pzccui"/><path class="zgl8s0sdh"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="n_1n94xtx"/><path class="hu1l55dbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compress-context-duotone-bold" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.gf7pzccui {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 8.5 12 11l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hu1l55dbx {
  d: path("M9.5 15.5 12 13l2.5 2.5");
}

.lx3jyybfn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n_1n94xtx {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x87wa6b5t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgl8s0sdh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 15.5 12 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
