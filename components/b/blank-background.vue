<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGFvN9Qb0m)" class="h_2o4qw3t"/><path fill="url(#SVGDptlvbrk)" class="a-eq1bc_s"/></g><defs><linearGradient id="SVGFvN9Qb0m" x1="7" x2="14.499" y1="6.001" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="wjpmzabvz"/><stop offset=".21" class="q1j9onbfh"/><stop offset=".39" class="ibt7x66qo"/><stop offset=".53" class="r_xkoac5f"/><stop offset=".77" class="nwfwfdbpw"/><stop offset="1" class="pmnlsetjd"/></linearGradient><linearGradient id="SVGDptlvbrk" x1="17.748" x2="7.249" y1="6.5" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="x9hl5mork"/><stop offset="1" class="hvza1bbfi"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blank-background" /></template>
<style>
.a-eq1bc_s {
  d: path("M11.999 4c-1.315 0-2.56.32-3.65.88a8 8 0 0 0 8.81 13.234a7.998 7.998 0 0 0-5.16-14.113m-3 2.5L17.5 9l-1.25 7.25L7.75 14z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h_2o4qw3t {
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16M8.5 7.5l7.999 2.25l-1.25 7l-8-2.25z");
}

.hvza1bbfi {
  stop-color: var(--svg-color--c7fe02, #c7fe02);
}

.ibt7x66qo {
  stop-color: var(--svg-color--62e700, #62e700);
}

.nwfwfdbpw {
  stop-color: var(--svg-color--142417, #142417);
}

.pmnlsetjd {
  stop-color: var(--svg-color--406925, #406925);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1j9onbfh {
  stop-color: var(--svg-color--2b6f04, #2b6f04);
}

.r_xkoac5f {
  stop-color: var(--svg-color--66e604, #66e604);
}

.wjpmzabvz {
  stop-color: var(--svg-color--337c01, #337c01);
}

.x9hl5mork {
  stop-color: var(--svg-color--43c601, #43c601);
}

</style>
