<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="gzk5d2xwl"/><path class="b9mcxsbuu"/><path class="u28r8ebnq"/><path class="nptuosbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-party-sharp" /></template>
<style>
.b9mcxsbuu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 13.75h.01m4.49 0h.01");
}

.gzk5d2xwl {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nptuosbjw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10.38a6 6 0 0 1 7 0M12 3.25h.01M4.75 5.5l1 1.25m13.5-1.25l-1 1.25");
}

.u28r8ebnq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 17l.88 1.1h2.74l.88-1.1M12 4.75l-3.5 5.63a6 6 0 0 1 7 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
