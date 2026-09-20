<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nur-ljbdo"/><path class="qrltb1_5z"/><path class="b0oa_xphd"/><path class="u33kgqbtd"/><path class="cmz4hzb5r"/><path class="r-k_ekbaq"/><path class="f9t4wkbqv"/><path class="ugh4qacil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:error-handler-duotone-bold" /></template>
<style>
.b0oa_xphd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cmz4hzb5r {
  d: path("M2 12h6l4 -4h5");
}

.f9t4wkbqv {
  d: path("m19 14 3 3");
}

.nur-ljbdo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h6l4 -4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qrltb1_5z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r-k_ekbaq {
  d: path("m8 12 4 4h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u33kgqbtd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m22 14 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ugh4qacil {
  d: path("m22 14 -3 3");
}

</style>
