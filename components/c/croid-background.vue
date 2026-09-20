<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGwGsZf84k)" class="r4i437pya"/><path class="dy08mubvf"/></g><defs><linearGradient id="SVGwGsZf84k" x1="12" x2="12" y1="5.499" y2="18.499" gradientUnits="userSpaceOnUse"><stop class="xksgjjh8u"/><stop offset=".49" class="or0j0tpqr"/><stop offset="1" class="xra1mjbbv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:croid-background" /></template>
<style>
.dy08mubvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.5 5.499a.5.5 0 1 0 0 1h4v11h-4a.5.5 0 1 0 0 1H9a.5.5 0 0 0 .5-.5v-12a.5.5 0 0 0-.5-.5zm7 0a.5.5 0 0 0 0 1h2c1.01 0 2.4.41 3.53 1.315A5.16 5.16 0 0 1 19 11.999c0 .384-.04.824-.135 1.284a.53.53 0 0 0 .2.55c.285.2.685.07.76-.27c.125-.565.175-1.1.175-1.565c0-2.27-1.02-3.904-2.345-4.964A6.98 6.98 0 0 0 13.5 5.499zm5.74 11.345c.19.22.16.554-.09.71a6.77 6.77 0 0 1-3.65.944h-2a.5.5 0 1 1 0-1h2c1.29 0 2.28-.29 3.05-.75a.55.55 0 0 1 .69.095M4.5 7.498a.5.5 0 0 0 0 1h2v1.5a.5.5 0 0 0 1 0v-2a.5.5 0 0 0-.5-.5zm6.5.5a.5.5 0 0 1 .5-.5h2c.5 0 1.17.1 1.84.37c.26.11.35.42.21.665c-.135.235-.43.32-.685.225c-.5-.185-.995-.26-1.365-.26h-2a.5.5 0 0 1-.5-.5m6.97 3.4a.456.456 0 0 0-.47-.4c-.315 0-.55.294-.52.61c.01.124.015.25.015.39c0 1.435-.59 2.284-1.29 2.794a3.97 3.97 0 0 1-2.205.706h-2a.5.5 0 1 0 0 1h2c.75 0 1.855-.22 2.79-.895c.965-.69 1.71-1.84 1.71-3.605q0-.315-.03-.6M4.5 9.999a.5.5 0 0 1 .5.5v3.5a.5.5 0 1 1-1 0v-3.5a.5.5 0 0 1 .5-.5m7 0a.5.5 0 0 0 0 1h2c.145 0 .39.04.605.15c.21.1.35.25.41.47a.5.5 0 1 0 .97-.24a1.72 1.72 0 0 0-.93-1.125a2.45 2.45 0 0 0-1.055-.255zm-.5 3.5a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1h-1.5a.5.5 0 0 1-.5-.5m-3.5.5a.5.5 0 0 0-1 0v1.5h-2a.5.5 0 1 0 0 1H7a.5.5 0 0 0 .5-.5zm0-2a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0m9-2a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m-1.5 3a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0m3.5 3.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.ft5dv1b6b {
  fill: none;
}

.or0j0tpqr {
  stop-color: var(--svg-color--73cd8d, #73cd8d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xksgjjh8u {
  stop-color: var(--svg-color--30c2c2, #30c2c2);
}

.xra1mjbbv {
  stop-color: var(--svg-color--d6773d, #d6773d);
}

</style>
