<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGP7QKIbHv)" class="dp3nxrb0p"/><path fill="url(#SVGdJucubbK)" class="qmk11qbip"/><path class="qigkkcz4z"/></g><defs><linearGradient id="SVGP7QKIbHv" x1="4.137" x2="11.286" y1="2.57" y2="18.052" gradientUnits="userSpaceOnUse"><stop offset=".26" class="vc--wpv5i"/><stop offset=".84" class="xotn8pxis"/></linearGradient><linearGradient id="SVGdJucubbK" x1="14.313" x2="19.245" y1="2.55" y2="19.927" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xotn8pxis"/><stop offset=".94" class="vc--wpv5i"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:govi-background" /></template>
<style>
.dp3nxrb0p {
  d: path("M7.997 17.906c.061.509.57.824 1.247.617l9.704-6.367c.494-.354.48-1.06-.202-1.492L8.59 4.056c-.236-.15-.593.019-.593.301v3.186l6.188 3.958l-6.188 3.958z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qigkkcz4z {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.089 6.987l-2.965 1.92l2.927 1.855l2.937-1.897zm.743 8.523l-2.974-1.882l-2.861 1.807v.183l2.875 1.836z");
}

.qmk11qbip {
  d: path("M15.997 19.319c-.06.508-.54.823-1.228.616l-9.704-6.183a1.035 1.035 0 0 1 .198-1.7L15.428 5.47c.245-.15.57.019.57.301v3.106l-6.279 4.038l6.278 3.958z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xotn8pxis {
  stop-color: var(--svg-color--95c9e3, #95c9e3);
}

</style>
