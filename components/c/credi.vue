<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGi7Jz4dAD)" class="wnk5fj8yp"/><defs><linearGradient id="SVGi7Jz4dAD" x1="3.011" x2="20.97" y1="12.001" y2="12.001" gradientUnits="userSpaceOnUse"><stop offset=".03" class="pzfnzkkiy"/><stop offset=".21" class="ma0petzpk"/><stop offset=".38" class="vvfags7mr"/><stop offset=".55" class="m4s4wve_m"/><stop offset=".72" class="rn3c2vbbx"/><stop offset=".89" class="k0h4ooblt"/><stop offset="1" class="aqdayt9ng"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:credi" /></template>
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

.m4s4wve_m {
  stop-color: var(--svg-color--255ca4, #255ca4);
}

.ma0petzpk {
  stop-color: var(--svg-color--1e3d8f, #1e3d8f);
}

.pzfnzkkiy {
  stop-color: var(--svg-color--1d398c, #1d398c);
}

.rn3c2vbbx {
  stop-color: var(--svg-color--2c78b7, #2c78b7);
}

.vvfags7mr {
  stop-color: var(--svg-color--214997, #214997);
}

.wnk5fj8yp {
  d: path("m9.582 12.638l3.26 3.274a.974.974 0 0 1 0 1.39L11.1 19.006c-.39.39-1.021.39-1.415 0l-6.392-6.323a.974.974 0 0 1 0-1.392l6.406-6.299a1.007 1.007 0 0 1 1.41 0l1.733 1.703a.973.973 0 0 1 0 1.396l-3.26 3.288a.88.88 0 0 0-.257.623c0 .228.087.457.257.637m6.791-2.505a.97.97 0 0 0 0-1.391l-.661-.652a1.004 1.004 0 0 0-1.416 0l-3.22 3.21a.974.974 0 0 0 0 1.396l3.22 3.201a1 1 0 0 0 1.41 0l.667-.652a.97.97 0 0 0 0-1.391l-1.518-1.44a.6.6 0 0 1-.18-.413a.6.6 0 0 1 .18-.428zm1.372.083L16.43 11.32a.97.97 0 0 0 0 1.39l1.314 1.086c.194.194.569.292.822.292c.258 0 .632-.098.827-.292l1.313-1.085a.98.98 0 0 0 .217-1.073a1 1 0 0 0-.217-.318l-1.313-1.104a1.27 1.27 0 0 0-.827-.302c-.253 0-.633.102-.827.302z");
}

</style>
