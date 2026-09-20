<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGukehlc2v)" class="r4i437pya"/><path class="k6119qb6n"/></g><defs><linearGradient id="SVGukehlc2v" x1="4.009" x2="19.973" y1="12.001" y2="12.001" gradientUnits="userSpaceOnUse"><stop offset=".03" class="pzfnzkkiy"/><stop offset=".21" class="ma0petzpk"/><stop offset=".38" class="vvfags7mr"/><stop offset=".55" class="m4s4wve_m"/><stop offset=".72" class="rn3c2vbbx"/><stop offset=".89" class="k0h4ooblt"/><stop offset="1" class="aqdayt9ng"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:credi-background" /></template>
<style>
.aqdayt9ng {
  stop-color: var(--svg-color--3bb7e1, #3bb7e1);
}

.ft5dv1b6b {
  fill: none;
}

.k0h4ooblt {
  stop-color: var(--svg-color--349bce, #349bce);
}

.k6119qb6n {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.851 12.567l2.897 2.91a.866.866 0 0 1 0 1.237L11.2 18.227a.893.893 0 0 1-1.258 0L4.26 12.606a.865.865 0 0 1 0-1.237l5.695-5.6a.895.895 0 0 1 1.254 0l1.539 1.514a.867.867 0 0 1 0 1.241l-2.897 2.923a.78.78 0 0 0-.23.554c0 .203.079.406.23.566m6.036-2.227a.863.863 0 0 0 0-1.236l-.588-.58a.893.893 0 0 0-1.258 0l-2.863 2.854a.865.865 0 0 0 0 1.241l2.863 2.845a.887.887 0 0 0 1.254 0l.592-.58a.864.864 0 0 0 0-1.236l-1.349-1.28a.53.53 0 0 1-.16-.367a.52.52 0 0 1 .16-.38zm1.22.074l-1.168.981a.863.863 0 0 0 0 1.237l1.168.964c.172.173.505.26.73.26c.23 0 .562-.087.735-.26l1.168-.964a.866.866 0 0 0 0-1.237l-1.168-.981a1.13 1.13 0 0 0-.735-.268c-.225 0-.562.09-.735.268z");
}

.m4s4wve_m {
  stop-color: var(--svg-color--255ca4, #255ca4);
}

.ma0petzpk {
  stop-color: var(--svg-color--1e3d8f, #1e3d8f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.pzfnzkkiy {
  stop-color: var(--svg-color--1d398c, #1d398c);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rn3c2vbbx {
  stop-color: var(--svg-color--2c78b7, #2c78b7);
}

.vvfags7mr {
  stop-color: var(--svg-color--214997, #214997);
}

</style>
