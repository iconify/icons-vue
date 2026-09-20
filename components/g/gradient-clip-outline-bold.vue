<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n_s7qxbob"/><path class="c4ap_p0of"/><path class="s2ui7wbye"/><path class="mfc7nxp-y"/><path class="du_3_4tit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gradient-clip-outline-bold" /></template>
<style>
.c4ap_p0of {
  d: path("M12 4v15");
}

.du_3_4tit {
  d: path("M4 21.5h16");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.n_s7qxbob {
  d: path("M6 10v9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s2ui7wbye {
  d: path("M18 12v7");
}

</style>
