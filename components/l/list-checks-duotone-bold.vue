<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wvd8g1bvl"/><path class="irvb5ybul"/><path class="xu_xghh-o"/><path class="bhlvvmwkr"/><path class="w3rpd0b7a"/><path class="tzpsmib8n"/><path class="dm_ar8wjk"/><path class="z5u11lbdo"/><path class="z4f7qacqo"/><path class="g9c4ykb9u"/><path class="myi37dz6l"/><path class="syk7o8b5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:list-checks-duotone-bold" /></template>
<style>
.bhlvvmwkr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dm_ar8wjk {
  d: path("m3 7 2 2 3 -3");
}

.g9c4ykb9u {
  d: path("M11 12h10");
}

.irvb5ybul {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.myi37dz6l {
  d: path("m3 17 2 2 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.syk7o8b5x {
  d: path("M11 17h10");
}

.tzpsmib8n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 17h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w3rpd0b7a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 17 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wvd8g1bvl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 7 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xu_xghh-o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 12 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z4f7qacqo {
  d: path("m3 12 2 2 3 -3");
}

.z5u11lbdo {
  d: path("M11 7h10");
}

</style>
