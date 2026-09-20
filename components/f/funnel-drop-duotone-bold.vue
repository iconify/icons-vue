<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uda6dfbwy"/><path class="tmfei69qh"/><path class="t3rzvj9ww"/><path class="m_77io35t"/><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funnel-drop-duotone-bold" /></template>
<style>
.c3wl0l-ou {
  d: path("M19 13v6");
}

.m_77io35t {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3rzvj9ww {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tmfei69qh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uda6dfbwy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wlp3ibbib {
  d: path("M6 13h12");
}

.yhbiuccel {
  d: path("m16 16 3 3 3 -3");
}

</style>
