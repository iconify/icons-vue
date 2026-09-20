<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJnx1275S)" class="r4i437pya"/><path class="p7wrcabbh"/></g><defs><linearGradient id="SVGJnx1275S" x1="18.42" x2="10.08" y1="19.91" y2="5.169" gradientUnits="userSpaceOnUse"><stop offset=".11" class="sxbkb1bax"/><stop offset=".18" class="m5_197hjz"/><stop offset=".33" class="uhfh96vkv"/><stop offset=".53" class="zbk47lqvs"/><stop offset=".81" class="v-4uj_b9h"/><stop offset=".97" class="mkujud60v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m5_197hjz {
  stop-color: var(--svg-color--ba6bff, #ba6bff);
}

.mkujud60v {
  stop-color: var(--svg-color--3fc, #3fc);
}

.p7wrcabbh {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.585 9.89l-9.18 3.26c-.5.18-1-.25-.905-.76l.85-4.62a.67.67 0 0 1 .24-.406l3.98-3.21a.685.685 0 0 1 .865 0l4 3.225c.115.095.2.22.235.36l.35 1.335c.09.34-.1.695-.435.815m-10.61 5.545l-.46 2.34c-.06.3.084.6.354.735A13.5 13.5 0 0 0 12.005 20c1.175 0 3.5-.155 6.075-1.46a.76.76 0 0 0 .405-.825l-1.1-5.85a.685.685 0 0 0-.91-.516l-10.05 3.576a.68.68 0 0 0-.45.51");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sxbkb1bax {
  stop-color: var(--svg-color--c65cff, #c65cff);
}

.uhfh96vkv {
  stop-color: var(--svg-color--9991ff, #9991ff);
}

.v-4uj_b9h {
  stop-color: var(--svg-color--42f0db, #42f0db);
}

.zbk47lqvs {
  stop-color: var(--svg-color--6cf, #6cf);
}

</style>
