<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4adGVdvM)" class="r4i437pya"/><path class="jl948ub4r"/></g><defs><linearGradient id="SVG4adGVdvM" x1="15.277" x2="6.596" y1="7.571" y2="10.555" gradientUnits="userSpaceOnUse"><stop class="htf9l1c4b"/><stop offset=".28" class="ou5k7ebjw"/><stop offset=".5" class="welg51r1o"/><stop offset="1" class="brdc_achv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:1art-background" /></template>
<style>
.brdc_achv {
  stop-color: var(--svg-color--a672dc, #a672dc);
}

.ft5dv1b6b {
  fill: none;
}

.htf9l1c4b {
  stop-color: var(--svg-color--836df7, #836df7);
}

.jl948ub4r {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.937 4.245c.976-.619 2.304.005 2.33 1.077v13.323c0 .747-.778 1.355-1.6 1.355c-.81 0-1.584-.592-1.6-1.333V8.405s-2.17 1.35-3.216 1.888a.94.94 0 0 1-.41.112c-.182 0-.374-.032-.56-.101c-.614-.235-1.174-.827-1.147-1.504c.016-.395.192-.768.581-1.024l.022-.016l5.6-3.52z");
}

.ou5k7ebjw {
  stop-color: var(--svg-color--2e8aca, #2e8aca);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.welg51r1o {
  stop-color: var(--svg-color--4978d6, #4978d6);
}

</style>
