<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGpZatKefN)" class="r4i437pya"/><path class="e20nxybly"/><path class="t3w7_cqms"/></g><defs><linearGradient id="SVGpZatKefN" x1="19.488" x2="4.121" y1="12.046" y2="12.504" gradientUnits="userSpaceOnUse"><stop class="w2cgp3_xd"/><stop offset="1" class="jtfc-e_le"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arc-background" /></template>
<style>
.e20nxybly {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.02 5.906a.73.73 0 0 0-.595-.306a.74.74 0 0 0-.594.297L5.83 14.286c.85-.61 1.78-1.096 2.765-1.445l3.818-5.335l3.643 5.266c.919.307 1.783.732 2.574 1.248zM4.457 18.048L4 18.4q.132-.166.457-.352c1.847-1.357 5.573-3.565 8.791-3.735c4.389-.228 7.164.91 6.702 2.272c-.462 1.363-3.698-.457-6.702-.457c-2.638 0-7.237 1.052-8.79 1.92");
}

.ft5dv1b6b {
  fill: none;
}

.jtfc-e_le {
  stop-color: var(--svg-color--041c28, #041c28);
  stop-opacity: 0.1;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.t3w7_cqms {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.788 15.63c-3.804 0-7.95 1.846-9.546 2.77L4 18.034c1.627-.942 5.86-2.834 9.788-2.834c3.488 0 5.133.654 5.627.887a.21.21 0 0 1 .105.288a.24.24 0 0 1-.31.091c-.426-.197-2.003-.837-5.422-.837");
}

.w2cgp3_xd {
  stop-color: var(--svg-color--197eaf, #197eaf);
}

</style>
