<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGZNgUIbcf)" class="r4i437pya"/><path clip-rule="evenodd" class="rd_z1rrdh"/></g><defs><linearGradient id="SVGZNgUIbcf" x1="6.987" x2="16.975" y1="7.569" y2="18.225" gradientUnits="userSpaceOnUse"><stop class="zcdpmwbwm"/><stop offset="1" class="mbf0j5w9r"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mbf0j5w9r {
  stop-color: var(--svg-color--5a49ff, #5a49ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rd_z1rrdh {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.67 7.797a14.9 14.9 0 0 1-5.346 6.428a14.9 14.9 0 0 1-7.958 2.538A8.04 8.04 0 0 1 7.542 5.618a8.01 8.01 0 0 1 11.127 2.18m.33-.05v-.995a.06.06 0 0 1 .03-.05l.89-.505a.054.054 0 0 1 .076.021q.006.015.004.03v.995q.001.015-.004.03a.1.1 0 0 1-.02.02l-.892.505a.054.054 0 0 1-.076-.022a.1.1 0 0 1-.008-.029m-.498 9.146A8.05 8.05 0 0 0 20 12.218a8 8 0 0 0-.835-3.56c-2.505 3.24-4.092 7.024-4.596 11.092c1.584-.542 2.96-1.493 3.933-2.857");
}

.zcdpmwbwm {
  stop-color: var(--svg-color--aa42fc, #aa42fc);
}

</style>
