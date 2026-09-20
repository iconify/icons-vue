<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGPEgN9bFc)" class="r4i437pya"/><path class="v715aeviy"/><path class="ckzelnbzx"/><path class="a4gsk-b8h"/></g><defs><linearGradient id="SVGPEgN9bFc" x1="19.28" x2="4.228" y1="6.007" y2="6.007" gradientUnits="userSpaceOnUse"><stop class="mme4rdgfu"/><stop offset=".47" class="im_xjub1l"/><stop offset="1" class="h8dpxis2p"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:haka-background" /></template>
<style>
.a4gsk-b8h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.877 19.778a8 8 0 0 0 6.069-6.869c-.49.146-.998.273-1.487.381a6.6 6.6 0 0 1-4.577 5.025v1.458z");
}

.ckzelnbzx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.485 19.984a7.997 7.997 0 0 0 6.101-12.523v1.246h-.88q.134.232.245.47h.635v2.824a6.586 6.586 0 0 1-5.212 6.445zm-.25.01v-1.412a7 7 0 0 1-.47 0v1.412a8 8 0 0 0 .47 0m-.72-.01A7.997 7.997 0 0 1 5.414 7.461V12a6.586 6.586 0 0 0 5.212 6.445zm6.587-13.158A8 8 0 0 0 12 4.003a7.98 7.98 0 0 0-6.097 2.823h2.023A6.55 6.55 0 0 1 12 5.414a6.55 6.55 0 0 1 4.074 1.412z");
}

.ft5dv1b6b {
  fill: none;
}

.h8dpxis2p {
  stop-color: var(--svg-color--7826f4, #7826f4);
}

.im_xjub1l {
  stop-color: var(--svg-color--d41b81, #d41b81);
}

.mme4rdgfu {
  stop-color: var(--svg-color--4fb585, #4fb585);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v715aeviy {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.53 7.295H5.884v3.294h2.823v2.879l.94 1.825V9.648H6.826V8.236h3.764v9.41l.94 1.806zm6.586 2.353v.94h-2.352v2.8l-.038.018l.038.005l-2.352 4.234l-.941 1.882V7.295h5.645v.941h-4.704v7.683l1.41-2.625V9.648z");
}

</style>
