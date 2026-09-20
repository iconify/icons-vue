<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bbm2pcpjp"/><path class="e91vxg_4v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:evmos-background" /></template>
<style>
.bbm2pcpjp {
  fill: var(--svg-color--dbd4c5, #dbd4c5);
  d: path("M24 0H0v24h24z");
}

.e91vxg_4v {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.062 7.741c-2.695.973-2.942 3.459-3.713 4.616c-.78 1.177-2.572 2.05-2.326 2.65c.082.205.357.267.738.267H6.33c.385 0 .919.008 1.148.07c1.067.287 2.462 1.177 4.259 1.169a5.2 5.2 0 0 0 1.793-.296a4.57 4.57 0 0 0 2.765-2.72a.21.21 0 0 0-.052-.218a.2.2 0 0 0-.14-.06a.23.23 0 0 0-.214.114a3.6 3.6 0 0 1-1.994 1.74c-.43.143-.88.212-1.333.205a3.93 3.93 0 0 1-2.905-1.174a3 3 0 0 1-.517-.77a3.5 3.5 0 0 1-.217-.534c.808-.353 1.67-.796 2.728-1.178c1.038-.369 2.396-.677 3.24-.919c.493-.143 1.178-.381 1.7-.377c.118 0 .143.115.176.205c.094.246.164.644.205.898a.18.18 0 0 0 .1.118a.18.18 0 0 0 .154-.003c.39-.197.743-.418 1.059-.599c1.05-.607 1.682-1.132 1.715-1.468a.25.25 0 0 0-.017-.12c-.078-.184-.394-.23-.898-.23a8.6 8.6 0 0 0-1.494.12c-2.937.505-6.162 1.32-8.902 2.494c-.009-1.456.927-2.687 2.461-3.24c.463-.152.95-.217 1.436-.194c.455.009.944.05 1.366.206a.24.24 0 0 0 .246-.054a.2.2 0 0 0 .058-.14a.21.21 0 0 0-.12-.188c-1.197-.607-2.699-.882-4.073-.39");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
