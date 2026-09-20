<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pygpyvjpl"/><path class="h3f5lcksx"/><path class="irk9zbcmx"/><path class="sn8xn_jdy"/><path class="v_tvvoixq"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="l517yxbln"/><path class="n4e83dijt"/><path class="g6ulbfs0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-gen-duotone-regular" /></template>
<style>
.el0n_ccnv {
  d: path("M8 5v14");
}

.g6ulbfs0a {
  d: path("M15 11h6");
}

.h3f5lcksx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.irk9zbcmx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l517yxbln {
  d: path("M12 9v6");
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.n4e83dijt {
  d: path("M18 8v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pygpyvjpl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sn8xn_jdy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v_tvvoixq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
