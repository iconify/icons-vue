<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n1ccfobwd"/><path class="x8232_bgk"/><path class="yw3eho_ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chalet-sharp" /></template>
<style>
.n1ccfobwd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.22 11.13l8.31-6.51l.47-.37l.47.37l8.31 6.51l.47.37H18.5v9.75h-13V11.5H2.75zm.53 4.12h16.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x8232_bgk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.75h.01");
}

.yw3eho_ht {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-3h3v3");
}

</style>
