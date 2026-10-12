<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="gzk5d2xwl"/><path class="b9mcxsbuu"/><path class="j0oij0bje"/><path class="nptuosbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-party" /></template>
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

.j0oij0bje {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17c.6.75 1.3 1.1 2.25 1.1s1.65-.35 2.25-1.1M12 4.75l-3.5 5.63a6 6 0 0 1 7 0Z");
}

.nptuosbjw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 10.38a6 6 0 0 1 7 0M12 3.25h.01M4.75 5.5l1 1.25m13.5-1.25l-1 1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
