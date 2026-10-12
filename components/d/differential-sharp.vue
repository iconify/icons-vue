<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l3bjokh7m"/><circle class="nl0pxj_sf"/><path class="c7sv0ijom"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:differential-sharp" /></template>
<style>
.c7sv0ijom {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.48 9.57v-.78h1.04v1.18l.28.11l.27.11l.28-.28l.27-.26l.28-.28l.29.28l.16.16l.28.29l-.28.28l-.26.27l-.28.28l.11.27l.11.28h1.18v1.04h-1.18l-.11.28l-.11.27l.28.28l.26.27l.28.28l-.28.29l-.16.16l-.29.28l-.28-.28l-.27-.26l-.28-.28l-.27.11l-.28.11v1.18h-1.04v-1.18l-.28-.11l-.27-.11l-.28.28l-.27.26l-.28.28l-.29-.28l-.16-.16l-.28-.29l.28-.28l.26-.27l.28-.28l-.11-.27l-.11-.28H8.79v-1.04h1.18l.11-.28l.11-.27l-.28-.28l-.26-.27l-.28-.28l.28-.29l.16-.16l.29-.28l.28.28l.27.26l.28.28l.27-.11l.28-.11z");
}

.l3bjokh7m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.75h4v2.5h-4zm14.5 0h4v2.5h-4zm-6.5 6.5h2.5v4h-2.5z");
}

.nl0pxj_sf {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
