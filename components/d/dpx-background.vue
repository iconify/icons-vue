<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGRDAm6cxQ)" class="r4i437pya"/><path class="xcv4sbcyk"/></g><defs><linearGradient id="SVGRDAm6cxQ" x1="12.026" x2="12.001" y1="11.211" y2="20.003" gradientUnits="userSpaceOnUse"><stop class="jkkb9kb7z"/><stop offset="1" class="v52i5ubzb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dpx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jkkb9kb7z {
  stop-color: var(--svg-color--22e1ff, #22e1ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.v52i5ubzb {
  stop-color: var(--svg-color--002eff, #002eff);
}

.xcv4sbcyk {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.302 9.005L9.476 4l-4.73 4.79a.725.725 0 0 0 .334 1.213l2.505.644a8.4 8.4 0 0 0-.674 1.277c-.2.453-.32.938-.35 1.432a1.96 1.96 0 0 0 .54 1.477c.417.441.915.797 1.467 1.048l.08.04c.39.177.72.467.943.834l.12.164c.458.65 1.187 1.667 2.12 2.346c.537.407 1.176.66 1.847.728c.793.05 1.58-.172 2.23-.629c.729-.479 1.208-1.008 1.437-1.621a2.76 2.76 0 0 0-.01-1.787c-.15-.504-.399-1.023-.639-1.502l-.044-.09a11 11 0 0 1-.664-1.572c-.32-1.047-.1-1.497.03-1.676a.75.75 0 0 1 .324-.24l.005-.005h.015l.025-.01l.115-.04l.3-.1q1.117-.379 2.235-.768q.053-.022.105-.05c.05-.03.1-.065.14-.105a.64.64 0 0 0 .164-.608a.7.7 0 0 0-.115-.24l-.065-.08l-.16-.18Q16.829 6.34 14.537 4l3.194 5.07q-.81.28-1.622.549l-.095.03h-.01q-.173.05-.33.14a2 2 0 0 0-.648.558c-.45.59-.639 1.498-.24 2.82c.2.643.49 1.237.744 1.761l.025.05c.25.52.464.948.584 1.347c.118.313.128.655.03.974c-.1.274-.35.608-.944.998a2.27 2.27 0 0 1-1.447.429a2.44 2.44 0 0 1-1.217-.5c-.759-.548-1.363-1.396-1.847-2.065l-.11-.15a3.36 3.36 0 0 0-1.412-1.227l-.084-.05a3.5 3.5 0 0 1-1.118-.799c-.115-.115-.18-.274-.17-.539c.005-.28.1-.614.25-.978c.3-.728.778-1.412.968-1.671a.73.73 0 0 0-.4-1.143zm5.29 5.195s-.968 0-1.612-.6c-.644-.598 0-1.8 0-1.8s.19.12.898.958c.714.843.714 1.442.714 1.442");
}

</style>
