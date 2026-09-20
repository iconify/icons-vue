<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1LyCHcjS)" class="r4i437pya"/><path class="rqs6p57zg"/></g><defs><linearGradient id="SVG1LyCHcjS" x1="16.969" x2="7.493" y1="5.951" y2="18.537" gradientUnits="userSpaceOnUse"><stop class="mu6yehrol"/><stop offset=".59" class="od5f7ageo"/><stop offset="1" class="zg8kp4hfd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aurora-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mu6yehrol {
  stop-color: var(--svg-color--95e141, #95e141);
}

.od5f7ageo {
  stop-color: var(--svg-color--63b836, #63b836);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rqs6p57zg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.672 6.38a1.867 1.867 0 0 0-3.35 0l-5.056 9.583a1.867 1.867 0 0 0 1.675 2.705h10.112a1.87 1.87 0 0 0 1.871-1.784a1.9 1.9 0 0 0-.196-.92zM9.367 5.9a2.934 2.934 0 0 1 5.26 0l5.06 9.583a2.932 2.932 0 0 1-2.634 4.251H6.94a2.944 2.944 0 0 1-2.635-4.25l5.061-9.58z");
}

.zg8kp4hfd {
  stop-color: var(--svg-color--409c2d, #409c2d);
}

</style>
