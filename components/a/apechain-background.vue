<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m0c6i0bgb"/><g clip-path="url(#SVGRaaGCb4g)"><path class="gxw_cq56r"/><path class="ng09jqb2g"/></g></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath><clipPath id="SVGRaaGCb4g"><path class="rhhzaiz7g"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apechain-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gxw_cq56r {
  stroke: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--2-256px, 2.256px);
  d: path("M19.808 6.024H4.196a.143.143 0 0 0-.144.143v11.907c0 .079.064.143.144.143h15.612c.08 0 .143-.064.143-.143V6.167a.143.143 0 0 0-.143-.143Z");
}

.m0c6i0bgb {
  fill: var(--svg-color--0054fa, #0054fa);
  d: path("M24 0H0v24h24z");
}

.ng09jqb2g {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.726 8.827H8.99l.816 6.784H8.734l-.12-1.476h-.567l-.12 1.476H6.91zm.504 3.016l-.11 1.394h.422l-.12-1.394l-.082-1.173h-.028zm3.825 3.768h-1.091V8.827h1.43c.779 0 1.256.459 1.256 1.284v1.668c0 .816-.477 1.274-1.256 1.274h-.34zm.009-3.373h.238c.183 0 .257-.165.257-.459v-1.668c0-.303-.074-.468-.257-.468h-.238zm2.842 3.373V8.827h2.127v.899h-1.036v2.007h.926v.899h-.926v2.08h1.036v.899z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rhhzaiz7g {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 6h16v12.232H4z");
}

</style>
