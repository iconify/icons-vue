<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGkDR02bqE)" class="uywdp2b-i"/><path fill="url(#SVGM7Qc9cYT)" class="xpo-vcctt"/><defs><linearGradient id="SVGkDR02bqE" x1="16.504" x2="13.928" y1="5.905" y2="20.348" gradientUnits="userSpaceOnUse"><stop class="niyiqjple"/><stop offset="1" class="q67t54x_p"/></linearGradient><linearGradient id="SVGM7Qc9cYT" x1="7.348" x2="12.048" y1="16.27" y2="3.004" gradientUnits="userSpaceOnUse"><stop class="logecd39c"/><stop offset="1" class="qr3w4v82z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bsw" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.logecd39c {
  stop-color: var(--svg-color--1158f1, #1158f1);
}

.niyiqjple {
  stop-color: var(--svg-color--ff496a, #ff496a);
}

.q67t54x_p {
  stop-color: var(--svg-color--e42648, #e42648);
}

.qr3w4v82z {
  stop-color: var(--svg-color--119bed, #119bed);
}

.uywdp2b-i {
  d: path("M18.99 6.39c-.631.125-1.222.3-1.712.406a3.06 3.06 0 0 0-2.398 2.68c-.202 1.4.27 2.003.062 3.635c-.36 2.843-3.096 3.828-4.368 4.419a305 305 0 0 1-3.906 1.728A9.006 9.006 0 0 0 19.051 6.402l-.068-.011z");
}

.xpo-vcctt {
  d: path("M10.996 10.687c.692-1.498.444-1.503.968-2.91a2.02 2.02 0 0 1 2.015-1.396c.518 0 1.058.163 1.289.191c.94.13 1.182-.208 3.169-.523l.281-.04A9 9 0 0 0 3.875 8.131c2.978.732 6.186 2.336 7.12 2.556M9.026 4.58c.264.039 1.536 1.615 1.773 5.673c0 0-1.633-.394-1.987-1.238c-.287-.687.09-1.599.214-4.435m10.019 1.8l.016.018l-.073-.006c.023-.011.04-.011.057-.011M3.003 12.01c0-.721.084-1.42.242-2.083q.489.404 1.047.917c2.347 2.173 6.163 3.89 7.554 2.297h.005c-.253.338-1.17 1.317-3.022.985l-2.984 4.452a8.98 8.98 0 0 1-2.842-6.569");
}

</style>
