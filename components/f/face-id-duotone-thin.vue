<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gf0hswvuq"/><path class="pfjq2-b9j"/><path class="e9bhdvbgs"/><path class="ja9qpyb-y"/><path class="xmcykibok"/><path class="rc-__xbag"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-id-duotone-thin" /></template>
<style>
.a-r3j5f7z {
  d: path("M3 16v4h5");
}

.a71lhwniq {
  d: path("M16 4h5v4");
}

.dxxnlbcax {
  d: path("M3 8V4h5");
}

.dy-bj6bwq {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.e9bhdvbgs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gf0hswvuq {
  fill: currentColor;
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ja9qpyb-y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pfjq2-b9j {
  fill: currentColor;
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rc-__xbag {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u84sg0ngq {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xmcykibok {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xt7079b9x {
  d: path("M16 20h5v-4");
}

</style>
