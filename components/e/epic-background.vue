<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGzLxOpbSD)" class="r4i437pya"/><path class="o0y6wmbdn"/><path class="zlrpdpb1p"/><path clip-rule="evenodd" class="y9cegcu0k"/></g><defs><linearGradient id="SVGzLxOpbSD" x1="4.334" x2="20.334" y1="14.565" y2="14.565" gradientUnits="userSpaceOnUse"><stop class="xz_pvabhx"/><stop offset=".16" class="f3bdsbcvn"/><stop offset=".52" class="okd2qwb7g"/><stop offset=".83" class="ivgecuhqf"/><stop offset="1" class="ev_edqbkh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:epic-background" /></template>
<style>
.ev_edqbkh {
  stop-color: var(--svg-color--b68e5d, #b68e5d);
}

.f3bdsbcvn {
  stop-color: var(--svg-color--f9ce97, #f9ce97);
}

.ft5dv1b6b {
  fill: none;
}

.ivgecuhqf {
  stop-color: var(--svg-color--f7cf89, #f7cf89);
}

.o0y6wmbdn {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.234 14.353v-4.47l5.412-3.059l-1.647-.941l-5.647 3.059v6.117l5.647 3.294l5.647-3.058v-1.883l-5.647 3.059z");
}

.okd2qwb7g {
  stop-color: var(--svg-color--b08656, #b08656);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xz_pvabhx {
  stop-color: var(--svg-color--b28947, #b28947);
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.zlrpdpb1p {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.588 8l.706-.47l1.411.94l-.705.471zm-4.942 4.47v-1.646l4.471-2.589l1.412.942zm6.824-1.883l-5.647 3.295l1.412.94l4.235-2.587zm1.177.943l-.94.47v-1.647l.94-.47z");
}

</style>
