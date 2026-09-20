<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lylvx0jgf"/><path class="avupa06-m"/><path class="e8pl9ubyd"/><path class="df_t0x8bu"/><path class="ns4vl7b2c"/><path class="n_s7qxbob"/><path class="c4ap_p0of"/><path class="s2ui7wbye"/><path class="mfc7nxp-y"/><path class="du_3_4tit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gradient-clip-duotone-regular" /></template>
<style>
.avupa06-m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c4ap_p0of {
  d: path("M12 4v15");
}

.df_t0x8bu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.e8pl9ubyd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lylvx0jgf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.n_s7qxbob {
  d: path("M6 10v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ns4vl7b2c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s2ui7wbye {
  d: path("M18 12v7");
}

</style>
