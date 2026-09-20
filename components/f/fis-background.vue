<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ai8puql6s"/><path class="b8n74u0fo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fis-background" /></template>
<style>
.ai8puql6s {
  fill: var(--svg-color--00f3ab, #00f3ab);
  d: path("M24 0H0v24h24z");
}

.b8n74u0fo {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.76 16.794l-.12.023c-.36.171-1.057.44-1.914.629L7.246 20H9.69l1.109-3.491a38 38 0 0 0-1.629.211l-.354 1.177zm1.12-2.411a7.3 7.3 0 0 1 1.697-.314L12 12.726l.4 1.331a5.2 5.2 0 0 1 1.714.349L12.52 9.714h-1.234l-1.412 4.669zm5.04 2.44l.366 1.074l.051-.971l.914.257l.286.086c.229.057.48.102.726.12L16.726 20h-2.52l-1.069-3.52c.617.074 1.234.206 1.783.343m2.743-1.372a11 11 0 0 1-1.132-.131a5 5 0 0 1-1.091-.314v-.046L17.497 4H20l-2.343 11.451zm-11.314.132L4 4h2.503l2.143 10.857l-.452.212c-.308.142-.577.268-.817.348c-.326.114-.686.154-1.028.166");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
